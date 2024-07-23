# Credit Risk Analysis Report

## Overview of the Analysis
The purpose of this analysis is to train and evaluate a logistic regression machine learning model's ability to predict loan risk. The analysis was conducted on financial data, specifically focusing on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, number of derogatory marks, and total debt. The objective was to predict the loan status, either as a healthy loan (0) or high-risk loan (1).

The stages of the machine learning process in this analysis included: 
1. Split the data into training and testing datasets
2. Create and fit a logistic regression model with the original data
3. Evaluate the model's performance
4. Write a Credit Risk Analysis Report

Methods used in this analysis include: Logistic Regression.

## Results
### Description of the machine learning model's accuracy score, the precision score, and recall score
<img width="477" alt="Screenshot 2024-07-22 at 8 40 06 PM" src="https://github.com/user-attachments/assets/01b5141d-0695-4c7f-b8ac-10d6584a70e2">

Accuracy:
* The accuracy score is 99%, which tells us that this model performs exceptionally well. Therefore, I recommend using this model for predicting customer's loan status.

Precision & Recall:
* For Class 0 (Healthy Loan), the precision was 1.00, recall was 0.99, and the F1-score was 1.00. This shows that the model has high precision and recall, indicating that it predicts healthy loans accurately and raraely misclassifies them.
* For Class 1 (High-Risk Loan), the precision was 0.84, recall was 0.94, and the F1-score was 0.89. This model has lower precision compared to Class 0. Only 84% of the predicted high-risk loans are correct, so there is a chance that it may predict some healthy loans as high risk loans. The recall is still relatively high, which tells us that the model correctly identifies a good portion of the actual high-risk loans.

## Summary
Based on the results, I would recommend using this model to predict the creditworthiness of loan borrowers, because it has a 99% accuracy rate. This shows that it is incredibly reliable. This model will help the company effectively assess loan applications and make informed decisions when approving or rejecting loans, thus mitigating credit risk. I recommend to continue to assess this model to minimuze the possiblity of errors occuring. 
