# credit-risk-classification

## Overview of the Analysis

* The dataset has a information about loan size, interest rate, borrow income, debt to income, number of accounts, derogatory marks, total debt and loan status. With all this information if the loan is granted or refused was predicted. Using  loan status as a target label.

* Loan Status was categorised as 0- healthy loan and 1- high-risk loan. Total count of healthy loan was 3653 and high risk loan was 1576. These values were reduced by dropping duplicate values as that was making data biased with too many values for loans granted.

* Generally the stages of machine learning include preprocessing, train, validate and predict. In this data the divided into features and target and then split in train and test model. Then followed by creating logistic regression model on original and resampled data.

* LogisticRegression() method was used to create a classification model to predict binary outcome .

## Results

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy Sore: 90%
  * Precision Score: 94% for helathy loans(0's), 82% for high-risk loans (1's)
  * Recall Score: 92% for 0's and 87% for 1's


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy Sore: 93%
  * Precision Score: 99% for 0's, 83 % for 1's
  * Recall Score: 91% for 0's , 97% for 1's

## Summary

* Which one seems to perform best? How do you know it performs best?
Based on these results, Model 2 outperforms model 1 in terms of accuracy, precision recall for both the classes.

* Does performance depend on the problem we are trying to solve? 
  Model 2 apprears to be better choice due to its superior performance in correcly identifying high-risk loans with a recall score of 97% on bad loans.

