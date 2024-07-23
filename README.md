# Credit-Risk-Classification
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions
1. Split the data into training and testing datasets
2. Create and fit a logistic regression model with the original data
3. Evaluate the model's performance
4. Write a Credit Risk Analysis Report

## Results
### Description of the machine learning model's accuracy score, the precision score, and recall score

<img width="477" alt="Screenshot 2024-07-22 at 8 40 06 PM" src="https://github.com/user-attachments/assets/01b5141d-0695-4c7f-b8ac-10d6584a70e2">

Accuracy: 
* The accuracy score is 99%, which tells us that this model performs exceptionally well. Therefore, I recommend using this model for predicting customer's loan status. 

Precision & Recall: 
* For Class 0 (Healthy Loan), the precision was 1.00, recall was 0.99, and the F1-score was 1.00. This shows that the model has high precision and recall, indicating that it predicts healthy loans accurately and raraely misclassifies them.
* For Class 1 (High-Risk Loan), the precision was 0.84, recall was 0.94, and the F1-score was 0.89. This model has lower precision compared to Class 0. Only 84% of the predicted high-risk loans are correct, so there is a chance that it may predict some healthy loans as high risk loans. The recall is still relatively high, which tells us that the model correctly identifies a good portion of the actual high-risk loans.
