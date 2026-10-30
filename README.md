# QuantRisk Analytics

### Financial Risk Analysis Using Python

QuantRisk Analytics is a beginner-level financial risk analysis project exploring two key areas: market risk and credit risk. It uses statistical techniques and Python to examine financial data, measure potential losses and understand credit default behaviour.

## Project Objectives

- Analyse movements and volatility in the Indian equity market.
- Measure potential market losses using Value at Risk and Expected Shortfall.
- Examine customer credit default behaviour.
- Apply logistic regression to estimate default probability.
- Evaluate model performance using classification metrics.

## Project Modules

### 1. Market Risk Analysis

**Dataset:** NIFTY 50 daily historical data, January to June 2026.

Analysis includes:
- Daily percentage returns
- Descriptive statistics
- Return distribution
- 20-day rolling volatility
- ARCH LM test
- Historical VaR at 95% and 99% confidence levels
- Expected Shortfall

### 2. Credit Risk Analysis

**Dataset:** Default of Credit Card Clients, UCI Machine Learning Repository.

A random sample of 500 observations was used.

Analysis includes:
- Customer repayment and credit information
- Logistic regression
- Probability of default
- Confusion matrix
- Accuracy, precision, recall and F1-score
- ROC-AUC evaluation

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## Repository Structure

```text
QuantRisk-Analytics/
├── data/
├── notebooks/
│   ├── 01_market_data_analysis.ipynb
│   └── 02_credit_risk_analysis.ipynb
├── src/
├── R/
├── outputs/
├── reports/
├── README.md
└── .gitignore
```

## Data Sources

- NIFTY 50: NSE / Nifty Indices
- Default of Credit Card Clients: UCI Machine Learning Repository

## Limitations

- The market-risk analysis uses approximately six months of daily observations.
- The credit-risk model uses a sample of only 500 customers.
- The credit dataset represents Taiwanese customers from 2005, not Indian borrowers.
- The credit model has limited default recall and is for educational purposes only.
- Historical risk estimates do not guarantee future market outcomes.

## Purpose

This project was developed to build practical familiarity with financial data analysis, statistical risk measurement and introductory credit-risk modelling using Python.
