# Logisctic Regression - Complete Guide

<a href="">Visit my Blog</a>

This Python code demonstrates how to use logistic regression to classify iris flowers based on their sepal length, sepal width, petal length, and petal width. The iris dataset is loaded from a CSV file using the pandas library, and then split into training and testing sets using the train_test_split function from the sklearn library. A logistic regression model is then trained on the training data and used to predict the class of the testing data. The accuracy and classification report are printed to the console.

# Logistic Regression
Logistic regression is a type of classification algorithm that is used to predict the probability of a categorical dependent variable based on one or more independent variables. It is a supervised learning algorithm, meaning that it requires labeled training data to learn from. Logistic regression is often used in machine learning and data science for binary classification problems, but can also be used for multi-class classification problems.

In logistic regression, the dependent variable is categorical and represents the class labels. The independent variables can be continuous, categorical, or a mix of both. The logistic regression model estimates the probability of the dependent variable taking a particular value based on the values of the independent variables. This probability is then transformed using the logistic function (also known as the sigmoid function) to produce a binary output (0 or 1) that represents the predicted class label.

# Requirements
This code requires the following libraries to be installed:

 - pandas
 - sklearn
