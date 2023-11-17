# Implementing_linear_regression

This repository contains implementations of linear regression to fit data using a set of periodic (trigonometric) basis functions. The basis functions take the form of 1, sin(x), sin(k ∗x), sin(2 ∗ k ∗ x), ..., where k is the frequency increment. The goal is to find the best fit for the data by varying the "function depth" (d) and parameter vector Θ. 

## Implementation
1. Using sklearn libraries
Developed a linear regression learner to solve the best fit problem for 1D data and handle different function depths up to depth 3.

2. Using NumPy, math, matplotlib libraries (Linear Regression from Scratch)
Developed linear regression learner using numpy and math libraries only to solve the best fit problem for 1-dimensional data and handle up to 3 functional depths.

## Plotting and evaluaton
Apply the regression learner to the dataset generated and plot resulting function for function depths 0, 1, 2, and 3.Evaluated the regression functions by computing the error on the test data points and plotted of the results.

## Results
The results include plots illustrating the fitted functions for different function depths and the corresponding error analysis.
