# Telco Customer Churn Prediction 📱📉

This machine learning project predicts customer churn for a telecom company using the Telco Customer Churn dataset. It involves data preprocessing, exploratory data analysis, model building, and evaluation to identify the most effective model for churn prediction.

---

## 📌 Problem Statement
Telecom companies face significant losses due to customer churn. The goal of this project is to build a model that can accurately predict which customers are likely to leave the service, so that proactive retention strategies can be applied.

---

## 📁 Dataset Overview
- Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Total Rows: 7,043
- Features: 21 (including customer demographics, account info, and service usage)
- Target Variable: `Churn` (Yes / No)

---

## 🔧 Process Summary
### 🧼 Data Preprocessing
- Handled missing values in `TotalCharges`
- Categorical feature encoding (LabelEncoding, OneHotEncoding)
- Feature scaling for numeric values

### 📊 Exploratory Data Analysis
- Checked churn distribution
- Visualized correlations and feature relationships

### 🤖 Model Training & Evaluation
- Models used:
  - Logistic Regression ✅ (Best model)
  - Random Forest
- Metrics evaluated: Accuracy, ROC-AUC, Classification Report

---

## ✅ Best Model: Logistic Regression
- **Accuracy:** 0.80 (example)
- **ROC-AUC Score:** 0.84 (example)
- **Reason:** Balanced performance and interpretability

---

## 💻 Tech Stack
- Python (Jupyter Notebook)
- Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

---

## 📝 How to Run
1. Clone this repo or download the files
2. Install dependencies:
   requirements.txt
