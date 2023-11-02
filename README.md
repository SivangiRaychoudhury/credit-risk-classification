# credit-risk-classification
 Supervised learning

## Overview of the Analysis
* The purpose of this analysis is to predict whether or not a loan is healthy (low risk) or high-risk, based on an individual's loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The logistic regression categorizes between the two types of loans, 0 - which is healthy loans and 1 - which is high-risk loans, and this is taken from the loan_status column.
* To acheive the goal, we have taken target(y) as loan_status and every other column as feature(X). After that we used train-test-split. At this point used the logistic regression on the original data and created the confusion matrix and then printed the classification report for the model.
* This analysis runs the logistic regression on the original data. 
  
## Results
- 94% balanced accuracy
- 80 healthy and 67 high-risk loans misclassified
- Healthy loans: 100% precision; high-risk loans: 87% precision

## Summary
The logistic regression model is successful at predicting both healthy (0) and high-risk (1) loan labels. It predicts healthy loans with 100% precise and high-risk loans at 87%. The balanced accuracy is at 94%. Also, the confusion matrix shows how only 80 healthy loans and 67 high-risk loans were misclassified, respectively.
