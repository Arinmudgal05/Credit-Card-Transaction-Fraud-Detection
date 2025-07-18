# Credit-Card-Transaction-Fraud-Detection
# 💳 Credit Card Fraud Detection using Anomaly Detection Techniques

This project focuses on identifying fraudulent transactions from credit card data using **unsupervised anomaly detection algorithms**. With the exponential growth in online transactions, it's critical to build models that can detect unusual patterns that may signify **financial fraud**.

---

## 🧠 Project Overview

- The dataset used contains credit card transactions made by European cardholders.
- It includes only numerical input variables resulting from a **PCA transformation**.
- The goal is to **detect frauds** using methods such as:
  - Isolation Forest
  - Local Outlier Factor (LOF)
  - One-Class SVM (SGDOneClassSVM)

These models are well-suited for **imbalanced datasets** and are effective for anomaly detection in high-dimensional spaces.

---

## 📂 Dataset

- The dataset (`creditcard.csv`) includes:
  - **Time**: Seconds elapsed between each transaction
  - **Amount**: Transaction amount
  - **V1–V28**: PCA-transformed features
  - **Class**: `0` for non-fraud, `1` for fraud

> 📉 Note: The dataset is highly imbalanced (fraud cases are ~0.17%).

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas, NumPy** – data handling
- **Seaborn, Matplotlib** – visualization
- **Scikit-learn** – modeling and evaluation

---




