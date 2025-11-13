---
title: Optimization for ML
layout: post
subtitle: Importance of optimization for ML
---

<span style="color: blue;">_**Note:-** This blog is under active development. I am currently reading a book, “Algorithms for Optimization” by Mykel J. Kochenderfer and Tim A. Wheeler. This book is freely available [here](https://algorithmsbook.com/optimization/){:target="*blank"}._</span>

### Introduction

Machine Learning is a category of algorithms which allows the computer to find a *function* on its own (without needing to explicitly programme the function) that completes a particular *task*. When the algorithm finds a desired function, then it is said that the machine has *learned* to complete a particular task. Machine learning is framed as an optimization problem, and because of this framing, a computer could learn to complete a task *on its own*. Once it is framed as an optimization problem, then one can use existing optimization algorithms. And we know that the optimization algorithm can find a *solution* (defined below) to the optimization problem on its own. So, this mystery of "computer learning to complete a task on its own without being explicitly programmed" gets solved when we realize that ML is nothing but an optimization problem.

<!-- Optimization problems and their corresponding algorithms are highly intuitive (that is, very easy to understand and a feeling that you know it already). And when ML is considered as nothing but an optimization problem then *all* the ML algorithms become intuitive. -->

<!-- It is hard to visualize spaces beyond three dimension and almost all the real problems deals with higher dimensional spaces. So, Another motivation to learn about optimization algorithms is that it will teach me how to work effectively with high dimensional spaces.  So, by learning optimization algorithms, one can  -->

### Optimization

For an optimization algorithm to find a solution on its own, one has to first define an objective function. An objective function takes the candidate solution as input and outputs a number denoting how well the desired objective is achieved. The output can either represent the goodness or badness, depending on how the objective function is defined. If output represents the goodness of the input (candidate solution), then input is *searched* for such that it maximises the objective function. The input which maximises the objective function is called a "solution" of the optimization problem.

### ML as an Optimization Problem

As mentioned in the first para, ML is framed as an optimization problem. The task which an ML algorithm learns to complete is used to define an objective function. The input to this objective function is nothing but a candidate function to complete a given task. The output of this objective function (in most cases) represents the badness, meaning it represents how badly the given candidate function (input of objective function) completes the task. So, the optimization algorithm finds a function which least badly completes the task, i.e., the *solution* of the optimization problem completes the task well.

<!-- And it learns it by looking at the data. -->
