# Project-2-Task-2-JunaidAhmedKhan
DevelopersHubs Corporation

# Loan Default Risk with Business Cost Optimization

## 📌 Project Overview

This project focuses on predicting the likelihood of loan default using machine learning and optimizing the decision threshold based on business cost analysis. The objective is not only to build an accurate classification model but also to minimize the financial impact of incorrect lending decisions by considering the costs of false positives and false negatives.

---

## 🎯 Objectives

- Clean and preprocess the loan application dataset.
- Train binary classification models:
  - Logistic Regression
  - CatBoost Classifier
- Evaluate model performance using classification metrics.
- Define business costs for False Positives (FP) and False Negatives (FN).
- Optimize the prediction threshold to minimize total business cost.
- Analyze feature importance to identify key factors influencing loan default.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost

---

## 📊 Dataset

This project uses the **Home Credit Default Risk – Application Train Dataset**, which contains customer application information and the target variable indicating whether a customer defaulted on a loan. The dataset is commonly used for credit risk prediction and binary classification tasks. :contentReference[oaicite:0]{index=0}

**Dataset Link (Kaggle):**

https://www.kaggle.com/datasets/datuman/home-credit-default-risk-train-data-tabular?utm_source=chatgpt.com

> **Note:** The `application_train.csv` dataset is too large to upload to this GitHub repository. You can check it directly from the Kaggle link above..

---

## 📈 Project Workflow

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- Handling Missing Values
- Feature Encoding and Scaling
- Train-Test Split
- Logistic Regression Model
- CatBoost Classification Model
- Model Evaluation
- Business Cost Optimization
- Decision Threshold Tuning
- Feature Importance Analysis
- Final Business Recommendations

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Business Cost Analysis

---

## 💡 Key Business Insight

Instead of relying solely on model accuracy, this project optimizes the prediction threshold based on business costs. By assigning different costs to False Positives and False Negatives, the model helps financial institutions make more profitable and risk-aware lending decisions.

---

## ✅ Results

- Successfully built and evaluated multiple binary classification models.
- Performed business cost optimization using threshold tuning.
- Identified the optimal threshold that minimizes total business cost.
- Analyzed the most influential features contributing to loan default risk.
- Provided actionable insights for improving credit risk assessment and loan approval strategies.
