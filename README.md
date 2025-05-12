# 📊 Linear Regression Techniques in Machine Learning

This repository contains a comprehensive Jupyter Notebook exploring various **Linear Regression techniques** for regression analysis. The goal of this project is to understand and compare the performance of different linear models including Ordinary Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net.

## 🚀 Overview

Linear regression is a fundamental algorithm in machine learning used for predictive modeling. In this notebook, we:

- Build and train models using multiple linear regression techniques.
- Evaluate model performance using **Root Mean Squared Error (RMSE)** and **R² Score**.
- Tune hyperparameters using **GridSearchCV** for optimal performance.
- Compare results across various models on training and testing datasets.

---

## 🧠 Techniques Covered

- ✅ Linear Regression  
- ✅ Ridge Regression (with GridSearchCV for optimal alpha)  
- ✅ Lasso Regression (with GridSearchCV)  
- ✅ Elastic Net Regression

---

## 📈 Evaluation Metrics Summary

| Model              | Train RMSE | Train R² | Test RMSE | Test R²  |
|--------------------|------------|----------|-----------|----------|
| **Linear Regression** | 9.775     | 0.985    | 10.538    | 0.982    |
| **Ridge Regression**  | 9.777     | 0.985    | 10.544    | 0.982    |
| **Lasso Regression**  | 9.775     | 0.985    | 10.539    | 0.982    |
| **Elastic Net**       | 9.782     | 0.985    | 10.555    | 0.982    |

All models performed well, with R² scores above **98%**, demonstrating that linear models can be powerful tools when applied appropriately to well-prepared data.

---

## 📂 Repository Contents

- `linear_regression_techniques.ipynb` – Jupyter notebook containing all implementations
- `README.md` – Project documentation and explanation

---

## 🛠️ Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (LinearRegression, Ridge, Lasso, ElasticNet, GridSearchCV)

---
