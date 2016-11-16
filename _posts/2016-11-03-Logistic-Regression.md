---
layout: post
title: Logistic Regression
categories: notes
---

Regression model is good at predicting continuous variables, but it is not a good solution for discrete-valued variables, such as $$y^{(i)}\in\{0,1\}$$. Instead, we use a different hypothesis to predict discrete-valued variables. For simplicity, we only consider to predict a discrete-valued variable with two possible values (0 and 1). This is called the binary classification problem.

Mathematically, we define the hypothesis function of this form:

$$
h_{\theta}(z) = \frac{1}{1 + e^{-z}}
$$

where $$z = {\theta}^{T}x$$

$$h_{\theta}(z)$$ is also called "sigmoid" or "logistic" function, denoted by $${\sigma}(z)$$. 
