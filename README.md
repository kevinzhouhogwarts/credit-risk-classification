# Credit Risk Analysis Report

## Overview
This analysis creates and assesses the performance of a logistic regression model on predicting high-risk and healthy loans.

## Model Performance
* The model accuracy is high. Among the test data, around 99.3% of loans were correctly predicted, whether high-risk or healthy.
* The precision for high-risk loans is 0.845; there were relatively many false positives.
* The precision for healthy loans is 0.998; there were very few false negatives.
* The recall of high-risk loans is 0.0.945.
* The recall of healthy loans is 0.994.

## Summary
In summary, the model does a relatively better job at predicting healthy loans than high-risk loans. However, if the goal of the model is to prioritize detecting high-risk loans (high recall), then it does well, at the expense of lower precision, occasionally misclassifying a healthy loan as high-risk. In this case, in which either the company or the lender peer would have to assume the cost of a loan default, then the model is recommended, since the opportunity cost of missing out on a healthy loan is relatively small compared to teh cost of a loan default.
