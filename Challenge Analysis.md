# Module 20 Challenge Analysis Report

## Overview of the Analysis

For this analysis two different test methods were used to analyze and predict the credit risk of customers within the provided dataset. The dataset included important factors such as loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total dabt and the area of interest for this analysis which was the status of the respective loans. For both analysis methods we split the loan status away from all the other variables and used the LogisticRegression for the original data and Resampled data using the RandomOverSampler module from imblearn. The second test also creates an equal amount of X and y value counts.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  - Accuracy: 0.9520479254722232
  - Precision: 0: 1.00, 1: 0.85
  - Recall: 0: 0.99, 1: 0.91



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  - Accuracy: 0.9945026387334079
  - Precision: 0.99
  - Recall: 0.99

## Summary

Based on our values listed above Model 2 is definitely a more accurate model and performs much better than Model 1. It must also be said that Module 1 provides a great insight into how accurate both models truly are with respect to each other. For this analysis, the outputs seem to suggest that there is more weight behind finding failure risk than success but this could also be tuned more with additional analyses and tests.


