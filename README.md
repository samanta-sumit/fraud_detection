# Fraud Detection Model using Machine Learning

##  Overview

This project aims to build a robust machine learning model that can detect fraudulent financial transactions. Fraud detection is a critical application of machine learning, especially in domains like banking and e-commerce, where real-time detection of anomalies can prevent significant financial losses.

---

## 🧠 Problem Statement

Fraudulent transactions are rare but costly. Due to the highly imbalanced nature of such datasets, traditional accuracy metrics are not reliable. Therefore, this project focuses on techniques to handle imbalance, engineer meaningful features, and evaluate models using ROC-AUC and recall-focused metrics.

---

## 📂 Dataset
- **Features** include:
  - Transaction amount
  - Type of transaction (`cash_out`, `transfer`, etc.)
  - Origin and destination account balance
  - Time and frequency of transactions
  - Class label: `0` (legit), `1` (fraud)

---

## 🔧 Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Modeling, evaluation, preprocessing
- **Imbalanced-learn (SMOTE)** – Handling class imbalance
- **Colab + GitHub** – Development and version control

---

## 🏗️ Project Workflow

1. **EDA (Exploratory Data Analysis)**
2. **Handling missing values and outliers**
3. **Feature Engineering**
4. **Multicollinearity Check using VIF**
5. **Data Preprocessing**
   - One-hot encoding
   - Scaling (if required)
6. **Train-Test Split (Stratified)**
7. **Handling Imbalance using SMOTE**
8. **Modeling**
   - Logistic Regression
   - Decision Tree
   - ✅ Random Forest (best ROC-AUC)
9. **Evaluation**
   - ROC-AUC
   - Confusion Matrix
   - Classification Report
  
  ##  Model Performance

| Metric        | Value     |
|---------------|-----------|
| ROC-AUC       | **0.8859** |
| Best Model    | **Random Forest** |

##  Key Predictive Features

- High transaction amount
- Use of `cash_out` and `transfer` payment types
- Frequent transactions in a short time window
- Deviation from customer's average transaction amount

---
