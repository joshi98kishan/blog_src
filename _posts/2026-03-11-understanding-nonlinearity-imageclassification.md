---
title: Understanding Non-Linearity in Image Classification
layout: post
subtitle: Trying to understand why image classification data is non-linear.
---

### Introduction
This has always bugged me that how image classification data is non-linear or not linearly separable. To understand this, we need to first understand the linear classifier.

### Linear Classifier

given a sample: $$y$$, $$[x_1, x_2, ...., x_k]$$, linear classifier first calculates this

$$z = w_1x_1 + w_2x_2 + ..... + w_kx_k + b$$

Then it classifies:

if $$z>0$$ then predict $$1$$
else        predict $$0$$

Linear classifier assigns weights to each feature. Then z is calculated via weighted sum of features and then bias is added to that weighted sum to calculate z.
z is a summation of k+1 real numbers. Classification is done on the basis of the sign of z. 

Now lets understand linear classifier via a feature space where each axis corresponds to each feature. Moving in the feature space corresponds to moving along multiple axes, each with different distances. Distance along a axis is the value of the corresponding feature. 

A linear classifier divides this space in two halves (here we do not care whether these halves are equal or not). Each half corresponds to a class, i.e., a point in one half corresponds to a class and a point in other half corresponds to another class. 

One important defining characteristic of the linear classifier is that these halves are contiguous. Lets understand it. You pick a axis $$i$$. Move from one end of this axis (-infinity) to another end (+infinity) while fixing the position in the other axes. [add example of such movement in 2d space. Fixing y and moving "parallel" to x axis]

Initially, the point is in one of the half. As movement continues, there comes a "boundary point" beyond which other half begins which then continues to positive infinity. 
z in this case becomes this:

$$z = m*x + c$$

where m is the weight of the picked feature and c is determined by fixed positions in other axes, their corresponding weights, and the bias term. Continuity of the half can be understood easily from this equation of line. Sign of z determines the half. Initially z is continouly of a particular sign then after the border point x=(-c/m), sign of z changes and remains same for the rest of the movement. This is true for any axis you pick for moving across.

Given a picked feature, sign of the weight of that feature determines whether one is moving from negative class to positive class or vice versa. If that weight is positive then one is moving from negative class to positive class. Which is obvious because initial value is negative infinity and final value is postive infinity.

[this para may not be needed]
One another defining property of a linear classifier is that it "fixes" the direction of movement for a given feature, which depends on the sign of weight. Which means that for a given feature and the sign of its weight, large enough and small enough values of this weight corresponds to each class.

Having said this. Let understand a linear classifier in one more way. Start with a sample of one of the half of the linear classifier. Now change the features of this sample such that one moves towards the other half. Whether to increase a feature or decrease a feature depends on its weights and the current half. If one is moving from negative half to postive half, then you need to increase features with positive weights and decrease the features with negative weights. 

For positive half, positive features are relatively bigger than negative features. And vice versa for negative half.  


### Circle Dataset
In this dataset, one can not find a linear classifier which perfectly classifies the classes. Because class is not defined by which particular feature should be relatively bigger than others. Class definition do not restrict particular features to be bigger or smaller rather it only restricts "vector length" where vector is defined by feature values. One class has bigger vector length than the other class. 

[define mathematically vector length]

A given vector length does not fixes which feature should be bigger and which should be smaller. A given vector length could come by increasing "any" set of features and decreasing accordingly other features. 

Lets understand this by first

A linear classifier fixes what feature should be big enough and what feature should be small enough for a particular half of a class. But samples of each class of this dataset are distributed such that it does not care which particular feature should be big and which feature should be small. It only care about the "set" of values. where elements of this set are the feature values. This set is permutation invariant that is a given element could come from any feature. It cares about the overall magnitude of the vector represented by this set. 

Talk about logistic regression. That is, it finds the classifier with least error and not least accuracy. Which means that it tries to reduce the distance of misclassified points from the decision boundary as much as possible. After convergence, logistic regression returns the best classifier in terms of this error. That is, one can not find a better classifier than this in terms of error. If there is no outlier, then this best error classifier is also the best classifier in term of accuracy. Having said this, for this dataset, the LR classifier is the best which can separate the two classes in terms of both error and accuracy.   


Lets consider this instance of a circle dataset and its corresponding best logistic regression classifer. 
[paste the plot here which contains circle dataset and linear classifier with positive and negative weight]

Check this. Even the best linear classifier fails to classify and it is barely better than random classifier. Because linear classifier is inherently limited for this non-linearly separable dataset.

Not only class label depends only on the permutation invariant set but also only on absolute values of the set elements. While linear classifier fixes the weight to each feature which in turn fixes the big enough and small values of a feature to different classes.

So, this dataset has properties which does not align with how linear classifier works.


### Image Classification
Image classification data is similar to circle dataset in the sense that class definition do not fix which features should be bigger and which should be smaller. Rather it depends on the "pattern" which could come from any set of features being bigger than other features. 

Pattern here means the particular manner the pixel changes in some area of a image. Area where this pattern occur could be anywhere in the image. This area could be a small part of the image or could span the whole image. E.g. the pattern for dog would be different than the pattern for cat.
Also this pattern could occur either with relatively larger pixel values than the non-pattern pixels or vice versa. If pattern pixels are relatively larger and as mentioned above this pattern could occur anywhere or could have any size then for some images this pattern will hit the negative weights and for other images it will hit the positive weights.


A class definition relies on just the shape of wave and do not care where this wave occurs, how big this wave occurs, or in what orientation it occurs. Meaning of wave here is with respect to the change in pixel values and not which particular pixel changes. Shape of the wave refers to the particular way this change in pixel values occurs as one moves across the image. This wave shape is a unique characteristic of a class and defines a class. A dog image will have a particular wave shape and a cat image will have a different wave shape. This particular change in pixel values could occur fastly or slowly, i.e., could occur in a small region of an image or could cover the whole image.

class is only a function of a pattern and this pattern could come from any subset of features (pixels in these case). This pattern over subset of pixels could span the whole image or could just reside in a small area of an image. 




