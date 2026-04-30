# CreditWise-Loan-System
ML-based system to predict loan approval and minimize risky approvals using precision-focused models.


# 💳 Credit Risk & Loan Approval Prediction

## 📌 Overview

ML system to predict loan approval while **minimizing false positives (risky approvals)**.

## 🎯 Problem

Avoid approving risky applicants while keeping approvals meaningful.

## ⚙️ Approach

* Data cleaning & encoding
* Feature engineering (Loan-to-Income, Savings ratio)
* Models: Logistic Regression, KNN, Naive Bayes
* Metric focus: **Precision**

## 📊 Results

* Best Model: **Naive Bayes**
* Precision: **~0.80**
* Reduced false positives

## 📈 Key Insight

Domain-based features > polynomial features

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```

## 🛠 Tech Stack

Python | Pandas | Scikit-learn | Matplotlib
