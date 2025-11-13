---
title: Linear Algebra for ML
layout: post
subtitle: A ramp which takes you from having school-level LA knowledge to mastery of LA required for ML.
---

<span style="color: blue;">***Note:-** This is only the first draft of this blog, I plan to add more to it.*</span>

<!-- I am currently reading a book titled "Linear Algebra" by Cherney et al. I will be editing this blog as my understanding about linear algebra grows. I will remove this note once I feel this blog is complete. -->

### Context
*If you haven't read previous blogs, here is some context:*

I want to become a fundamental AI researcher, and this is my sole goal. And I am preparing myself for it by writing blogs. I have explained in the previous blogs that blogging is perfect for me for two reasons - it helps me to properly understand a topic, and at the same time, it allows me to give a service of education. 

I am currently only good at school-level mathematics. So, **from this level, whatever more topics are required for the goal, I will be mastering them, and at the same time, I will write a blog on each topic mentioning all my understanding of that topic**. I am currently in a position where I know what topics I should learn, how I should learn them, and how well I should know those topics. These topics are divided into two major groups. The first group of topics is nothing but the maths required for Machine Learning (a way to implement AI), which I simply call “maths fundamentals”. That is, all the maths which is required to become a great AI researcher. The second group of topics will be on AI literature. 

Maths fundamentals is beyond the school-level mathematics. Subjects in maths fundamentals are linear algebra, probability, optimisation and other miscellaneous topics. Each subject in itself is a group of topics, and hence there will be a series of blogs for each subject. And then I will be writing a series of blogs on AI literature.

### Introduction

This is the first blog in the series of linear algebra (LA) for ML blogs. This blog is about -

- Why is LA important?
- Spirit of LA.

### Why is LA important?

*I have planned to write a dedicated blog on the importance of LA. I will link it here once I complete writing it. Below is a short overview of what I currently know about this.*

LA is important because of these reasons:

- It is easy to find a linear relationship. There is only one solution, you just find that particular solution. That is, there is only one way input and output can have a linear relationship. On the other hand, there are many ways you can find a non-linear relationship between them.
- It is highly interpretable. You know which variables impact how much to the result.
- There are many real-world phenomena which are inherently linear. E.g., the first half of the computation by a biological neuron is linear. And this is why artificial neurons are the way they are – a linear function followed by a non-linear function.

### Spirit of LA
Any subject has a particular spirit which is the cause of the origination of all the concepts of that subject. In this section, I want to talk about the spirit of LA and how every concept of LA originates from that spirit.

When you know why the particular concept exists, then you don’t need to memorise it. Because when you know why a concept exists, then this “why” triggers your problem-solving mindset. And since you have read that concept at least once, this helps you easily solve that problem for yourself. You become the creator of that concept. That concept feels natural to you, and you can create it on the fly whenever you forget the details of it. “Natural” here means that you know the concept without needing to memorise it, and you just need a way to bring it to your awareness.  And that way is to know the problem itself, i.e., why that concept exists.

_Working on the below grey colored text, which I will move to a dedicated blog._
<span style="color: grey;">The whole subject becomes a graph where nodes are concepts (or solutions) and edges are 'why' questions (or problems). And every node can be traced back to a root node, which is the spirit of the subject. And as you move towards the root, concepts become easy to understand. And the root concept, the spirit, is the easiest concept. To get the feel of its easiness, consider the concepts of addition, subtraction, etc., they are so easy that they are hard to forget.</span>

<span style="color: grey;">Once you understand the root, then you will naturally understand all the concepts. What this means is that you do not need to memorise all the concepts, either you will know them by heart, or if you do not remember them, then you will be able to recreate them on the fly.  After understanding the root, you will know which problems originate from it, which triggers your problem-solving mindset. That is, you will begin to solve the problem for yourself, you will begin to find the concept which solves this problem. And if you also read the solution (the concept which actually connects the edge) from some resource like a book, then it becomes easy to solve the problem yourself and arrive at that concept. Similarly, from that concept, the same process repeats. You will know the problem originating from this concept, and then you will solve it. By repeating this process, you will recreate all the concepts of that subject.</span> 

<span style="color: grey;">And later on, whenever you are stuck with some problem, you do not need to remember its solution, you can create the solution on the fly. You will create it easily because you will have some vague memory of the solution. You will start from whichever node you remember and build a solution for that problem. And if you do not remember intermediate nodes to that solution node, then you will definitely remember the root node, from where you can build your solution by first building the intermediate nodes.</span>

<span style="color: grey;">When you look at the subject as such a graph, then the whole subject looks like one unit. That is, every concept is coherently connected to each other. When you try to create the graph for yourself starting from the root node, you will know that the rest of the nodes are the only way one could create the graph of the subject.</span>

While reading the Cherney et al. LA book, I found the spirit of LA, which they have distinctively highlighted.

> "LA is the study of vectors and linear functions." [cite Cherney et al. LA book]
> 

A function is a *linear* function if it follows this:

$$T(u+v) = T(u) + T(v)$$

$$T(cu) = cT(u)$$

where $$c$$ is a scalar.

What I currently think is that even the concept of “vector” stems from the concept of “linear function” (also called “linear map”, “linear mapping”, “linear transformation” or “linear operator”). 

So, “linear function” is the spirit of LA, or it is the root concept of LA which defines LA. From “linear function”, all the concepts of LA originate but in the form of a tree data structure. That is, there are some concepts, namely "vector”, “vector space” and “matrix”, which directly originate from the root and hence are at the first level of depth from the root. A vector is nothing but the input or output of a linear function. A vector space is nothing but the space of all possible inputs or the space of all possible outputs. And a matrix is one way to represent a linear function, or it is a way to represent a collection of vectors.

Then from the first level, concepts originate which are at the second level of depth from the root. Concepts at this second level are eigenvector, eigenvalue, determinant, SVD, PCA and all other concepts of LA.
