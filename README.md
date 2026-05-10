# Credit Wise Loan Approval System

## 📌 Overview
**Credit Wise** is an end-to-end machine learning project that predicts loan approval status (Approved/Rejected) using supervised classification algorithms. The system performs **Binary Classification** based on applicant features such as income, credit history, loan amount, and more.

This project demonstrates a complete ML pipeline including:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building (Logistic Regression, K-Nearest Neighbors, Naive Bayes)
- Model Evaluation (Precision, Recall, F1-Score)

---

## 🎯 Problem Statement
Financial institutions receive thousands of loan applications daily. Manual processing is time-consuming and prone to bias. The goal is to build an automated system that accurately predicts whether a loan should be approved based on historical applicant data.

---

## 📁 Dataset.
The Dataset is uploaded for Understanding Purposes.

---

## 🧠 Machine Learning Pipeline

### 1. Exploratory Data Analysis (EDA)
- Checked missing values & outliers
- Visualized distributions (income, loan amount)
- Correlation analysis between features
- Target variable balance check

### 2. Feature Engineering
- Handled missing values (mode/mean imputation)
- Created new features 
- Encoded categorical variables (Label / One-Hot Encoding)
- Scaled numerical features (StandardScaler)

### 3. Model Training
Three algorithms were implemented and compared:

| Model | Description |
|-------|-------------|
| Logistic Regression | Baseline linear model for binary classification |
| K-Nearest Neighbors (KNN) | Distance-based classifier with k=5 |
| Naive Bayes (Gaussian) | Probabilistic classifier assuming feature independence |

### 4. Model Evaluation
Evaluation metrics used (since it’s an imbalanced classification problem):
- **Precision** – How many approved predictions were correct?
- **Recall** – How many actual approvals were captured?
- **F1-Score** – Harmonic mean of precision & recall

---

## 📊 Results Summary 

| Model | Precision | Recall | F1-Score |
|-------|-----------|--------|-----------|
| Logistic Regression | 0.78 | 0.83 | 0.80 |
| KNN (k=5) | 0.67 | 0.57 | 0.61 |
| Naive Bayes | 0.81 | 0.70 | 0.75 |

- Naive Bayes was choosen as the best model on the basis of Precision

---

## 🛠️ Tech Stack
- Python 3.8+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook / VS Code

---
## AUTHOR 
PRINCY JAIN
