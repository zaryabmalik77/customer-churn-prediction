# Customer Churn Prediction

## Week 1: Exploratory Data Analysis

### Dataset
- Source: Telco Customer Churn (Kaggle)
- Size: 7,043 customers, 21 features
- Target: Predict customer churn (Yes/No)

### Key Findings
- Month-to-month contract holders exhibit significantly higher churn rates compared to long-term commitments.
- Short tenure (0–12 months) is the strongest indicator of potential customer loss.
- High monthly charges correlate strongly with increased churn, especially for non-contracted plans.
- Fiber optic internet subscribers show a higher churn rate than DSL or non-internet users.
- Electronic check users demonstrate the highest churn rate among all available payment methods.

### Setup
Open the Kaggle notebook or run locally:
```bash
pip install pandas numpy matplotlib seaborn
