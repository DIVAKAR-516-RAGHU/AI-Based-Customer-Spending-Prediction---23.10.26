# AI-Based Customer Spending Prediction

## Project Overview
This beginner-friendly machine learning project classifies customers into Low, Medium, or High spending categories using demographic and income-related information.

## Objectives
- Clean and inspect customer data.
- Perform exploratory data analysis (EDA).
- Prepare features for machine learning.
- Train and compare Logistic Regression and Decision Tree classifiers.
- Evaluate the selected model using classification metrics and a confusion matrix.
- Generate predictions for new customer records.

## Dataset
- Total records: 200
- Features: Gender, age, and annual income
- Target: Spending category
- Categories: Low, Medium, High

## Models
1. Logistic Regression
2. Decision Tree

The model is selected based on Macro F1-score.

## Sample Prediction
A sample customer was classified as **Medium** spending.

## Key Findings
- Medium is the largest category, with 94 customers.
- High-spending customers have the lowest average age.
- Annual income alone does not determine spending behaviour.

## Tools and Technologies
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Note
Model performance should be assessed using the held-out test set. Predictions are educational estimates, not guaranteed descriptions of real customer behaviour.
