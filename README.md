# PRODIGY_ML_02
# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to perform **unsupervised customer segmentation** based on purchasing behavior. The goal is to help a retail store identify distinct groups of customers using their demographic and spending patterns.

---

## 📦 Dataset

- **Dataset Used**: [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- 📄 File: `Mall_Customers.csv`
- 🔢 Columns include:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## ✅ Project Overview

| Component         | Description                                  |
|------------------|----------------------------------------------|
| 🔍 Objective      | Cluster customers into meaningful groups     |
| 🧮 Features Used  | `Age`, `Annual Income`, `Spending Score`     |
| 📏 Preprocessing  | Standardized features using `StandardScaler` |
| 📊 Clustering     | `KMeans` from `sklearn.cluster`              |
| 📈 Evaluation     | Elbow Method to choose `k`                   |
| 🖼️ Visualization  | 2D plot with cluster labels and centroids    |

---

## 🧪 Results

- Optimal number of clusters: **5**
- Each cluster represents a distinct customer group based on spending habits and income
- Visualization includes colored scatter plot with **cluster names and centroids**

---

## 🛠️ How to Run

### ✅ Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
