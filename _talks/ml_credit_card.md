---
title: "Credit card fraud detection system."
collection: talks
type: "Project"
permalink: /talks/ml_credit_card
venue: "Department of Electrical Engineering, IIT Bombay"
date: 2019-02-14
location: "Mumbai, India"
---
[More information here](/images/ML_assignment_2.tar.gz)

* Project description: Developed an SVM model from scratch for classification of fraudulent credit card transactions on a dataset taken from Kaggle. 
  * Objective : Training Support Vector Machine for detecting Credit card fraud using given data.
  * Method Used: 200 samples are randomly take from the data file (100 each for positive and negative class) five times.
  * Trained the Model 5 times and obtained respective accuracies using 80% of the data for training and 20% for testing split.
  * Achieved accuracy of 92.5% by formulating an algorithm for convex quadratic optimization problem of dual form of SVM.
  * cvxopt library has been used for finding out the optimum solution for Lagrange Multipliers.
