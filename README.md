# Term Deposit Prediction | FinTech Analytics 📈

## Overview
This project analyzes customer and campaign data to predict whether a customer will subscribe to a **bank term deposit**.  
The use case closely aligns with **FinTech lending & banking analytics**, where data-driven targeting is critical for improving conversion rates and reducing operational costs.

The project demonstrates how **data analytics + machine learning** can support smarter marketing decisions in financial institutions.

---

## Business Context (Why This Matters in FinTech)
In banking and FinTech companies:
- Customer acquisition costs are high
- Mass marketing leads to low conversion
- Regulatory and operational efficiency is critical

By predicting **which customers are more likely to subscribe**, banks can:
- Run **targeted campaigns**
- Improve **ROI on marketing spends**
- Enhance **customer experience**
- Reduce unnecessary outreach

This mirrors real-world FinTech problems in **lending, deposits, and customer lifecycle analytics**.

---

## Problem Statement
Given historical marketing campaign data, predict whether a customer will subscribe to a **term deposit** (`Yes/No`).

**Target Variable:**  
- `y` → Term deposit subscription status

---

## Dataset Summary
- **Dataset**: Bank Marketing Dataset
- **Domain**: Banking / FinTech
- **Type**: Structured, tabular data

### Feature Categories:
- **Customer Demographics**: age, job, marital status, education
- **Financial Information**: account balance, loans
- **Campaign Attributes**: contact type, duration, number of contacts
- **Economic Indicators**: macroeconomic factors affecting decisions

---

## Analytical & Modeling Approach
### 1. Data Understanding
- Identified feature types (categorical & numerical)
- Checked missing values and class imbalance

### 2. Data Preprocessing
- Label encoding / one-hot encoding
- Handling imbalanced target variable
- Feature scaling (where required)

### 3. Exploratory Data Analysis (EDA)
- Subscription trends by age and balance
- Impact of campaign duration
- Effect of repeated contacts on customer response

---<img width="1111" height="628" alt="Image" src="https://github.com/user-attachments/assets/282d6140-d83a-4b64-a5ee-90bd63d8831d" />


### 4. Model Development
- Logistic Regression (baseline)
- Decision Tree Classifier
- Random Forest (performance comparison)

### 5. Model Evaluation
- Accuracy
- Precision & Recall (important in banking decisions)
- F1-score
- Confusion Matrix

---<img width="1485" height="680" alt="Image" src="https://github.com/user-attachments/assets/18ff4c10-a445-4cea-b004-6c4970f0fbeb" />

- <img width="1106" height="667" alt="Image" src="https://github.com/user-attachments/assets/edb68d23-5c8f-4a7f-a41d-91881a31beef" />


## Key Business Insights
- **Campaign duration** is the strongest predictor of subscription
- Customers with **higher balances** have higher conversion probability
- Excessive contact attempts reduce customer engagement
- Targeted strategies are more effective than blanket campaigns

These insights can directly support **marketing strategy optimization** in FinTech firms.



## Tools & Technologies
- **Python**
- **Jupyter Notebook**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
