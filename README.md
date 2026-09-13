# Customer Churn Prediction

## Week 1: Exploratory Data Analysis

### Dataset
- Source: Telco Customer Churn (Kaggle)
- Size: 7,043 customers, 21 features
- Target: Predict customer churn (Yes/No)

### Key Findings
- Month-to-month contract holders exhibit significantly higher churn compared to 1-year or 2-year commitments.
- Customers with short tenure (0–12 months) are at the highest risk of churning.
- High monthly charges strongly correlate with increased churn rates unless anchored by long-term commitments.
- Fiber optic internet subscribers experience noticeably higher churn than DSL or non-internet users.
- Electronic check users demonstrate the highest churn rate among all payment methods.

### Setup
Open the Kaggle notebook or run locally:
```bash
pip install pandas numpy matplotlib seaborn
