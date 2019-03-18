---
layout: post
title: Deriving Cross Entropy and MSE using Maximum Likelihood Estimation
comments: true
tags: ['Machine Learning Notes', 'Python']
image_url: mathematics.jpg
---

Mean Squared Error (MSE) and Cross Entropy are two of the commonly used cost functions in machine learning for regression and binary classifications problems respectively.

Given a set of $n$ training examples, mean squared error and cross entropy are defined as:

$$
\begin{align}
\frac{1}{n}\sum_{i=1}^n(y_i-\hat{y_i})^2
\end{align}
$$

$$
\begin{align}
-\frac{1}{n}\sum_{i=1}^n\bigg[y_i\log\hat{y_i} + (1 - y_i)\log(1 - \hat{y_i})\bigg]
\end{align}
$$

$y_i$ is the observed value (or label if it is a classification problem) of the $i^{th}$ training example, while $\hat{y_i}$ is the prediction for the $i^{th}$ example.

If you ever wondered why those cost functions are used, it turns out we can derive them if we frame linear regression and binary classification as Maximum Likelihood Estimation (MLE) problems. This 

### Likelihood function and Maximum Likelihood Estimation

### Framing linear regression as MLE

### Framing logistic regression as MLE

### Conclusion

