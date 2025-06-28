# Churn_Prediction

# 🧠 Churn Prediction System

This project is a machine learning solution that predicts whether a customer will leave a bank based on their profile and activity. By analyzing key factors using classification models, it supports strategic retention decisions for banks.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Installation](#installation)
- [Workflow](#workflow)
- [Model Evaluation](#model-evaluation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)

---

## 📖 Overview

The project uses a bank's customer dataset to build models that classify whether a customer is likely to churn (`Exited = 1`). It includes:

- Data preprocessing and transformation
- Feature engineering
- Training and evaluation of three classification models:
  - Logistic Regression
  - Random Forest
  - XGBoost

---

## 📊 Dataset

- **Source**: `Churn_Modelling.csv` from Kaggle
- **Target Variable**: `Exited`
- **Removed Columns**: `RowNumber`, `CustomerId`, `Surname`
- **Feature Engineering**:
  - `BalanceSalaryRatio = Balance / (EstimatedSalary + 1)`
- **Label Encoded Features**: `Gender`, `Geography`

---

## 💻 Technologies

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – data handling
  - `matplotlib`, `seaborn` – visualization
  - `scikit-learn` – preprocessing, modeling, evaluation
  - `xgboost` – gradient boosting model

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
   cd churn-prediction
