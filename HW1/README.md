# Introduction
UNIV. Of Oklahoma ECE 5973 HW1. A Repository makes a prediction to the stock price of MSFT based on the past price of several stocks 
using linear regression model and neural networks. Note that the prediction is focusing on the stock price of MSFT of the current time period rather than the future one.
# Test Data Set
## x_testing.csv
A excel file stores the price of several stocks for testing
# Train Data Set
## x_trainging.csv
A excel file stores the price of several stocks for training
# Approach
Using fully connected neural networks with 5 hidden layers. Each layer has 20 neurons and applying RELU as activation function.
## Optimization Algorithms
In order to optimize the "prediction", try multiple optimization algorithms.
* SGD
* Momentum
* Adam
## Learning Rate schedulers
Changes the learning rate during learning by the following schedulers.
* OneCycleLR
* CyclicLR
* ReduceLROnPlateau
