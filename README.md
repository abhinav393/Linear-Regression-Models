# Linear-Regression-Models
This repository tracks my progress in learning Machine Learning Algorithms, specifically Linear Regression, and the models I will develop with this knowledge.

Linear regression is one of the most basic forms of machine learning and is used to predict numeric values.
    
# How it Works?  
Regression is a form of supervised learning in which we try to predict a numerical output based on some number of inputs.
y = f(x).

Goal: Learn a general mapping, f, so that f(x_i) is roughly equal to y_i.
In linear regression, we assume that the mapping from X to Y takes the form of a linear equation. Just like in algebra, a line is generally described by
y = mx + b
Where m is a slope and b is the y-intercept.

# Finding Line of best fit: 
In general, we will not be able to find a line so that y_i = mx_i + b for each i. Most times, there will be a small error between the prediction, pi = mxi + b, and the observation, y_i. We will call this error e_i. We want to find the line which fits the data as well as possible, minimizing the error of the model.
The model error is often referred to as the cost function. Mean Squared Error (M.S.E) is a common error metric used in ML. The goal is to find a set of parameters m and b which minimizes the MSE. It is a common choice in ML because it results in a function which is differentiable everywhere.
