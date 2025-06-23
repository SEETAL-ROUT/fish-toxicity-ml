# Fish Toxicity Prediction using Machine Learning

This project involves building a machine learning model to predict **LC50 toxicity levels** in fish, based on chemical descriptors. The goal is to identify the toxicity of various chemicals using regression techniques, contributing to safer environmental and chemical assessments.

## 🔍 Project Overview

- **Problem Statement:** Predict the LC50 value (a measure of acute toxicity) of chemical compounds to fish using molecular descriptors.
- **Dataset:** Publicly available dataset from [UCI Repository / Kaggle].
- **Model Used:** Random Forest Regressor (best-performing), Linear Regression.
- **Performance:** R² score of **0.72** achieved after tuning with GridSearchCV.

## 🛠️ Features & Workflow

- Data cleaning and imputation of missing values.
- Outlier handling and preprocessing.
- Exploratory Data Analysis (EDA) using visualizations.
- Regression model training and evaluation using RMSE and R².
- Hyperparameter tuning using `GridSearchCV`.
- Visual analysis of feature importance.

## 📊 Tools & Technologies

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib

## 📈 Results

| Metric | Value |
|--------|-------|
| Best Model | Random Forest |
| R² Score | 0.72 |
| RMSE | [Insert your RMSE value here if available] |

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/fish-toxicity-ml.git
