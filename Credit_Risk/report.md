# Module 12 Report 

## Overview of the Analysis

The objective of this analysis was to utilize machine learning techniques, specifically logistic regression, to forecast credit risk. 

- **Purpose of Analysis**: The main aim was to identify whether a loan is at high risk of default or is likely to be a healthy loan. By predicting this, financial institutions can make better lending decisions.
  
- **Data Overview**: The dataset consists of financial metrics like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable, `loan_status`, indicates whether a loan is healthy (`0`) or at high risk (`1`).

- **Variables Information**: A preliminary investigation of the `loan_status` using `value_counts` provided insight into the distribution of healthy versus high-risk loans. However, precise numbers will require actual data for a comprehensive understanding.

- **Machine Learning Process**: The process involved reading the data, splitting it into training and test sets, creating and fitting a logistic regression model to the training set, and finally evaluating the model's performance using the test set.

- **Methods Used**: The primary model used for this analysis was `LogisticRegression`. Additional metrics used for evaluation include the balanced accuracy score, confusion matrix, and classification report.

## Results

* **Machine Learning Model 1: Logistic Regression**
  * **Balanced Accuracy Score**: The model achieved an accuracy of approximately 95.20%.
  * **Precision**: For predicting healthy loans (`0`), the model had a precision of 100%. For high-risk loans (`1`), the precision was 85%.
  * **Recall**: The recall for healthy loans was 99%, whereas for high-risk loans, it was 91%.



## Summary

Based on the analysis:

- The logistic regression model demonstrates robust performance, especially in predicting healthy loans.
  
- While the model effectively predicts a majority of high-risk loans, it does misclassify approximately 10% of them as healthy. This is an area where additional data or refinement might be beneficial.

- **Recommendation**: Given its high accuracy and precision, the logistic regression model is recommended for this application. However, the ultimate choice might depend on the specific business objective. If predicting high-risk loans (`1`) is of paramount importance due to potential financial implications, further tuning or supplemental models should be considered to reduce the false negatives.
