# credit-risk-classification

## Overview of the Analysis
In this challenge, we want to build a model that can identify the creditworthiness of borrowers.

we have 'loan_size'	'interest_rate'	'borrower_income'	'debt_to_income'	'num_of_accounts'	'derogatory_marks'	'total_debt'	to preditct 'value_counts'.

Data Splitting: 
Reading the lending_data.csv into Pandas DataFrames.
Splitting the data into training and testing sets using train_test_split.

Logistic Regression Model:
we fit LogisticRegression models to preditect the 'value_counts'.

## Results

* Machine Learning Model 1:

  training classification report

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619
    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

* Machine Learning Model 2:

  training classification report

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619
    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384


## Summary

In this challenge Model 2 is slightly better the Model 1 on accuracy, and it is more important to predict the `1`'s in this scenario.
