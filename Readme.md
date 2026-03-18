# 🏦 Customer Churn Prediction - Smart Bank

## Project Overview
This project focuses on predicting customer churn for a bank using machine learning techniques. The goal is to identify customers who are likely to leave the bank, enabling proactive retention strategies.

---

## Objective
- Build a machine learning model to predict churn (Yes/No)
- Handle imbalanced data effectively
- Optimize model performance based on business needs (recall-focused)
- Provide actionable business insights

---

## Dataset
- Multiple datasets merged using **Customer ID**
- Feature engineering performed to capture customer behavior, transactions, and engagement

---

## Data Preprocessing
- Removed irrelevant columns ( Customer ID)
- Handled missing values
- Encoded categorical variables
- Applied **StandardScaler** (for Logistic Regression)
- Train-test split
- Applied **SMOTE** to handle class imbalance

---

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting

---

## Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall (Primary focus)
- F1-score
- ROC-AUC

### Key Insight
- Accuracy was misleading due to class imbalance
- **Logistic Regression performed best in identifying churners**

---

## Threshold Tuning
- Default threshold (0.5) was not optimal
- Adjusted threshold to **0.4**
- Improved **recall to ~85%**, enabling better churn detection

---

## Results
- **Best Model:** Logistic Regression  
- **Recall (Churn Class):** ~85%  
- **ROC-AUC:** ~0.57  

---

## Business Impact
- Identifies high-risk customers early
- Enables targeted retention strategies
- Reduces customer churn and revenue loss

---
