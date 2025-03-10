# creditscore_202401100400133
# Credit Score Prediction

This project focuses on cleaning and transforming financial data to improve credit risk assessment models. The goal is to predict whether a borrower is likely to default on a loan based on their financial data.

---

## Problem Statement
The task involves:
1. Cleaning and preprocessing financial data (e.g., handling missing values, outliers, and inconsistencies).
2. Transforming the data into a format suitable for machine learning models.
3. Building a predictive model to classify borrowers as "High Risk" or "Low Risk."

---

## Features
- **Input Features**:
  - Age
  - Annual Income (₹)
  - Total Debt (₹)
  - Credit Utilization (%)
  - Months of On-Time Payments
  - Number of Credit Accounts
  - Loan Amount (₹)
- **Target Variable**: `Default` (1 = High Risk, 0 = Low Risk)

---

## Files
1. `credit_score_prediction.ipynb`: Jupyter Notebook containing the code.
2. `credit_score_model.pkl`: Pre-trained XGBoost model.
3. `report.md`: Report in Markdown format.
4. `README.md`: This file.

---

## How to Run
1. **Install Required Libraries**:
   ```bash
   pip install pandas xgboost joblib matplotlib
