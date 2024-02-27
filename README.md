# Credit Risk Classification

## Overview of the Analysis

The purpose of this assignment was to train and evaluate a machine learning model based on loan risk. I used a dataset of historical lending activity to build a model that can identify the creditworthiness of borrowers. 

The financial data that I used included the size and interest rate of each loan that was being taken out; the income of each borrower; the debt to income ratio of each borrower; the number of accounts each borrower has; derogatory marks; and the total debt of each borrower. I used this data to try to predict whether each loan that was being issued would be a healthy loan or a high-risk loan based on the profile of each borrower. The provided dataset had over 77,000 loans - 75,036 of those were healthy loans and 2,500 were high-risk loans.

The steps I took as part of this analysis include separating the "label" (loan status) from the "features" of the dataset. Next, I split the data into training and testing sets. After that, I fit a logistic regression model by using the training data. Then I saved the predictions on the testing data labels by using the testing feature data and the fitted model I just created. Finally, I evaluated the model's performance by generating an accuracy score, confusion matrix, and a classification report.

## Results

* Logistic Regression Model:
  * Accuracy = 99%
  * Precision = 100% of healthy loans and 87% of high-risk loans
  * Recall = 100% of healthy loans and 89% of high-risk loans

## Summary

This logistic regression model does a pretty good job of predicting creditworthiness. The results are better when predicting healthy loans, which makes sense because the dataset has far more of those than high-risk loans. I would recommend this model for a company that needs it based on its accuracy, precision, and recall scores. I think the model could benefit from gathering more data on high-risk loans so there would be more to train on, but overall, I think it is still good enough to use.