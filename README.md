# Customer-Churn-Prediction-Bank-Customers-
## Project Overview
This project aims to predict customer churn in a banking system using machine learning.  
Customer churn refers to customers who leave the bank. By predicting churn in advance, banks can take proactive steps to retain customers.

---

## Objective
- Identify customers who are likely to leave the bank
- Build a classification model for churn prediction
- Analyze important features that influence customer churn

---

## Dataset
**Churn Modelling Dataset**

The dataset contains demographic and financial information of bank customers such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership
- Estimated Salary

**Target Variable**
- `Exited`
  - 1 → Customer churned
  - 0 → Customer retained

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Data Preprocessing
The following preprocessing steps were performed:
- Checked for missing values
- Removed irrelevant columns:
  - RowNumber
  - CustomerId
  - Surname
- Encoded categorical variables:
  - Gender using Label Encoding
  - Geography using One-Hot Encoding
- Applied feature scaling using StandardScaler

---

## Model Training
- The dataset was split into:
  - 80% training data
  - 20% testing data
- A Random Forest Classifier was trained to predict customer churn
- The model learned patterns from customer behavior and financial data

---

## Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

These metrics were used to measure the performance of the churn prediction model.

---

## Feature Importance Analysis
Feature importance was extracted from the Random Forest model to understand churn behavior.

**Important features influencing churn:**
- Age
- Balance
- Number of Products
- Geography
- Active Membership

This analysis helps in understanding key factors behind customer churn.

---

## Project Structure
