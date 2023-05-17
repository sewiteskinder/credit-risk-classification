# credit-risk-classification

## Overview of the Analysis
The purpose of this analysis was to predict the credit-worthiness of borrowers for lending service companies to use. The financial information included in the data had loan size, interest rate, number of accounts, derogatory marks on accounts, borrower income, total debt, debt-to-income ratio, and loan status. In order to predict worthiness, loan status was used.
The machine learning process began with separating the dependent (loan_status) and independent variables in to y and X. Once our variables were separate, each one was split into a training and a testing dataset using sklearn's 'train_test_split' module. After separated into training and testing sets, using the LogisticRegression module from sklean the X and y training sets were fit into the module to make predictions and compare to the test datasets. 
The module's performance was evaluated by finding the balanced accuracy score, a confusion matrix was created to visualize the performance of the classification algorithm, and finally the classification report was printed.

## Results
- The balanced accuracy score gave a 94% accuracy rating for the module
- The precision score for healthy loan labels was 100%, and for the unhealthy loans/high-risk loans was 87%
- The recall score for healthy loan labels was 100%, and for the unhealthy/high-risk loans was 89%

## Summary
I would recommend the LR Model with Original Data, especially when predicting a healthy loan user. For the healthy loan user (0), it gave perfect predictions when using the module. For the unhealthy loan user (1), there still was a high prediction accuracy, but not as high as for the healthy loan user.
