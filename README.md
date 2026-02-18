# Credit Risk Analysis & Default Prediction

## 📌 Objective
This project analyzes financial indicators to predict loan default risk using Logistic Regression.

## 📊 Dataset
The dataset contains 2000 records with the following features:
- Income
- Age
- Loan
- Loan-to-Income Ratio
- Default (Target Variable)

## 🔍 Exploratory Data Analysis
- Default distribution analysis (class imbalance identified)
- Income vs Default comparison
- Loan-to-Income vs Default comparison
- Correlation heatmap analysis

## 🤖 Model
- Logistic Regression classifier
- Train-test split for evaluation

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC Score

## 🔎 Key Insights
- Loan-to-Income ratio is the strongest predictor of default risk.
- Higher income reduces default probability.
- The dataset shows moderate class imbalance (~10% defaults).

## 💼 Business Recommendations
- Applicants with high loan-to-income ratios should be flagged as high risk.
- Risk-based interest rates can be designed using model output.
- Model can support automated credit risk scoring systems.
