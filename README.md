# Credit Risk Classification Project

## Project Overview

This project seeks to apply machine learning techniques to forecast credit risk. By accurately predicting the risk associated with a loan, financial institutions can make better-informed lending decisions, minimizing potential losses and maximizing profitability.

### Dataset

The dataset used in this project comprises several financial metrics, including:

- Loan size
- Interest rate
- Borrower income
- Debt-to-income ratio
- Number of accounts
- Derogatory marks
- Total debt

The target variable, `loan_status`, indicates whether a loan is healthy (`0`) or high-risk (`1`).

## Objectives

- Process and clean the dataset for machine learning.
- Train a logistic regression model to predict the loan status.
- Evaluate the model's performance using various metrics like balanced accuracy score, confusion matrix, and classification report.

## Dependencies

This project uses the following libraries:

- pandas
- numpy
- scikit-learn
- pathlib

## Setup & Usage

1. Clone this repository to your local machine.
2. Ensure you have the necessary libraries installed.
3. Navigate to the project directory and run the main script (if provided) or follow the Jupyter notebook (if provided) to see the workflow and results.

## Results

The logistic regression model achieved:

- A balanced accuracy score of approximately 95.20%.
- Precision of 100% for predicting healthy loans and 85% for high-risk loans.
- Recall rates of 99% for healthy loans and 91% for high-risk loans.



