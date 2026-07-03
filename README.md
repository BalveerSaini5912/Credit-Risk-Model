# Credit Risk Default Prediction

## Problem Statement
Banks lose crores of rupees when they give loans 
to people who later default. This model predicts 
which applicants are likely to default before 
giving them a loan.

## Dataset
- Source: Kaggle — Give Me Some Credit
- Size: 150,000 borrower records
- Features: Age, Income, Debt Ratio, 
  Late Payments etc.

## Approach
1. Data cleaning and missing value treatment
2. Exploratory Data Analysis
3. Class imbalance handling using SMOTE
4. Model building — Logistic Regression and XGBoost
5. Feature importance analysis

## Results
| Model | ROC-AUC Score |
|-------|--------------|
| Logistic Regression | 65.32% |
| XGBoost Basic | 73.01% |
| XGBoost Improved | 74.85% |

## Key Findings
- Late payment history is strongest predictor
- Credit utilization ratio is second most important
- XGBoost outperformed Logistic Regression by 9.5%

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, 
XGBoost, Matplotlib, Seaborn, SMOTE

## How to Run
1. Open notebook in Google Colab
2. Upload cs-training.csv dataset
3. Run all cells in order

## Connect With Me
- LinkedIn: linkedin.com/in/balveer-saini
- GitHub: github.com/BalveerSaini5912
