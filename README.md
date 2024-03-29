# Credit Risk Classification Report

## Overview of the Analysis

The purpose of this analysis is to develop a machine learning model to predict credit risk based on various financial attributes. The dataset contains information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status (healthy loan or high-risk loan).

## Financial Information and Prediction

The data includes financial attributes such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal is to predict whether a loan is healthy (0) or high-risk (1) based on these attributes.

## Variables to Predict

The main variable of interest is the loan status, which indicates whether a loan is healthy (0) or high-risk (1).

## Machine Learning Process

Data preprocessing: The data was cleaned and prepared for analysis, including handling missing values and encoding categorical variables.
Data exploration: Exploratory data analysis was performed to understand the distribution and relationships between variables.
Model selection: Logistic Regression was chosen as the primary method for classification due to its suitability for binary classification tasks.
Model training: The logistic regression model was trained on the training dataset to learn the patterns in the data.
Model evaluation: The model's performance was evaluated on the test dataset using metrics such as accuracy, precision, recall, and F1-score.

## Results

Machine Learning Model Performance

### Logistic Regression Model:

* Accuracy: 0.99
* Precision for label 0 (healthy loan): 1.00
* Precision for label 1 (high-risk loan): 0.84
* Recall for label 0: 0.99
* Recall for label 1: 0.94
* F1-score for label 0: 1.00
* F1-score for label 1: 0.89

## Summary
The logistic regression model exhibits exceptional performance in predicting credit risk for both healthy and high-risk loans. It achieves an impressive accuracy score of 0.99, indicating its ability to correctly classify loans into their respective categories. The model's precision and recall scores further support its effectiveness, with high values for both labels.

The high precision for label 0 (healthy loans) suggests that the model rarely misclassifies healthy loans as high-risk. Similarly, the high recall for label 1 (high-risk loans) indicates that the model effectively captures a significant portion of high-risk loans. This balanced performance is crucial for minimizing the financial risks associated with misclassifying loans.

## Model Recommendation

The logistic regression model is recommended for use due to its high performance in predicting credit risk. It provides valuable insights into the likelihood of loans being high-risk, enabling better risk management decisions.

## Detailed Analysis

The logistic regression model's accuracy of 0.99 indicates that it correctly predicts 99% of the loan statuses. This high accuracy is crucial for ensuring that the model can effectively differentiate between healthy and high-risk loans, reducing the potential for financial losses.

The precision score for label 0 (healthy loans) is 1.00, indicating that when the model predicts a loan as healthy, it is correct 100% of the time. This is important for ensuring that the company does not mistakenly categorize healthy loans as high-risk, which could result in missed opportunities.

The precision score for label 1 (high-risk loans) is 0.84, indicating that when the model predicts a loan as high-risk, it is correct 84% of the time. While this precision score is slightly lower than for label 0, it is still relatively high, indicating that the model is effective in identifying high-risk loans.

The recall score for label 0 is 0.99, indicating that the model correctly identifies 99% of all actual healthy loans. This high recall score is essential for ensuring that the company does not miss any healthy loans that may be mistakenly categorized as high-risk.

The recall score for label 1 is 0.94, indicating that the model correctly identifies 94% of all actual high-risk loans. This high recall score is crucial for ensuring that the company can identify the majority of high-risk loans, reducing the potential for financial losses.

In conclusion, the logistic regression model is a valuable asset for the company, providing a robust framework for assessing credit risk in loans and aiding in sound decision-making processes. Its high accuracy, precision, and recall scores make it a reliable choice for predicting credit risk, enabling the company to make informed decisions while minimizing potential risks.
