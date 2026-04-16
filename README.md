# Telco Customer Churn — Econometric Analysis

## Problem
What customer, contractual, and pricing factors predict telecom churn?
Analyzed using a dataset of 7,043 customer records with 26.5% churn rate.

## Methods
- Exploratory Data Analysis (Python: pandas, matplotlib, seaborn)
- Linear Probability Model (OLS)
- Logit Model (MLE) with interaction terms
- Multicollinearity check via VIF — dropped TotalCharges

## Key Findings
1. Contract type is the strongest predictor — month-to-month customers 
   churn at 42.7% vs 2.8% for two-year contracts
2. Churn drops sharply after 12 months tenure — first year is highest risk
3. Electronic check users churn at 45.3% vs ~15% for auto-payment users

## Business Recommendations
1. Incentivize migration from month-to-month to annual contracts
2. Invest heavily in first-year onboarding and issue resolution
3. Target high-charge, short-tenure customers with loyalty offers pre-emptively

## Tools
Python | pandas | statsmodels | matplotlib | seaborn | sklearn
