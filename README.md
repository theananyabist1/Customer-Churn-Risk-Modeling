# Customer Churn Risk Modeling 🧠📉

This project focuses on building a supervised machine learning pipeline to predict customer churn based on behavioral and demographic data. It includes exploratory data analysis (EDA), model training and evaluation, and actionable insights that support customer retention strategies.

---

## 📌 Objective

To develop a predictive ML solution that identifies customers at high risk of churning, enabling proactive and targeted retention efforts.

---

## 🔍 Dataset

- **Source:** Kaggle / Simulated Banking Dataset
- **Size:** 10,000 rows × 14 features
- **Target Variable:** `Exited` (1 = churned, 0 = retained)

---

## 🔧 Tools & Libraries

- **Languages:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`
- **ML Models Used:**
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Gaussian Naive Bayes
  - Decision Tree Classifier

---

## 📈 Project Workflow

1. **Data Cleaning & EDA**
   - Checked for nulls, distributions, outliers
   - Analyzed churn distribution across features like Geography, Tenure, and Credit Score

2. **Feature Engineering**
   - Label encoding for categorical variables
   - Feature scaling where necessary

3. **Model Training & Evaluation**
   - Trained 7 classification models
   - Evaluated performance using Accuracy, Recall, Precision, and AUC
   - Compared models for business interpretability and reliability

4. **Insights & Business Impact**
   - Used feature importance techniques to interpret results
   - Identified churn patterns to support retention strategy design

---

## ✅ Results

- **Top Model Accuracy:** 89%
- **Precision Lift over Baseline:** +25%
- **Outcome:** Enables sharper targeting of at-risk customers using interpretable, data-driven insights.

---

## 📊 Future Scope

- Integrate Power BI dashboard for interactive business visualizations
- Implement automated churn score for new customer data
- Deploy via Flask or Streamlit as a decision-support tool

---

## 📁 Repository Structure

