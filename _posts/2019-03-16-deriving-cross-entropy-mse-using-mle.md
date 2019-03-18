---
layout: post
title: Deriving Mean Squared Error (MSE) and Cross Entropy cost functions using Maximum Likelihood Estimation
comments: true
tags: ['Machine Learning Notes', 'Python']
image_url: mathematics.jpg
---

Mean Squared Error (MSE) and Cross Entropy are commonly used cost functions in machine learning for regression and binary classifications problems respectively.

Given a set of $n$ training examples, mean squared error and cross entropy are defined as:

$$
\frac{1}{n}\sum_{i=1}^n(y_i-\hat{y_i})^2
$$

$$
-\frac{1}{n}\sum_{i=1}^n\bigg[y_i\log\hat{y_i} + (1 - y_i)\log(1 - \hat{y_i})\bigg]
$$

$y_i$ is the observed value (or label if it is a classification problem) of the $i^{th}$ training example, while $\hat{y_i}$ is the prediction for the $i^{th}$ example.

If you have ever wondered why those cost functions are used, the choice becomes apparent when we frame linear regression and binary classification as Maximum Likelihood Estimation (MLE) problems. 

### What is Maximum Likelihood Estimation?
Suppose we have a sample $X = (X_1, ..., X_n)$ of independently and identically distributed (iid) random variables drawn from a probability distribution whose parameter $\theta$ we do not know. We often want to use the random data we have to estimate the value of the parameter. Maximum Likelihood Estimation is one of the estimation methods used.
### Framing linear regression as MLE

### Framing logistic regression as MLE

### Conclusion

