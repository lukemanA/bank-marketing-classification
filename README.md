# Bank Marketing Campaign — Predictive Classification Model

This project builds a machine learning pipeline to predict whether a customer will subscribe to a bank term deposit based on a phone marketing campaign.

## 📊 Project Overview
* **Problem Type**: Binary Classification
* **Models Evaluated**: Logistic Regression, Random Forest, Gradient Boosting
* **Key Finding**: Discovered that `duration` introduces heavy data leakage, and optimized the decision threshold to 0.35 to maximize **Recall** for the marketing team.

## 🛠️ Tech Stack & Tools
* Python 3
* Pandas & NumPy (Data Cleaning & Preprocessing)
* Scikit-Learn (Pipelines, ColumnTransformer, Machine Learning Models)
* Matplotlib (Data Visualization)

## 📈 Key Results
* **Best Model**: Random Forest (Highest Recall of 77.22% and F1-Score of 75.40%)
* Lowering the prediction threshold to 0.35 successfully caught more subscribers, aligning perfectly with the bank's preference for minimizing lost opportunities.
