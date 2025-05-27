# Fraud Detection System

This project is a **machine learning-based fraud detection system** built using Python and scikit-learn. It predicts the likelihood of a transaction being fraudulent based on various input features such as transaction amount, location, age, and merchant information.

## 📌 Overview

Credit card fraud is a growing problem in the financial sector. This project demonstrates the use of **Gradient Boosting Classifier** and **SMOTE (Synthetic Minority Oversampling Technique)** to build a reliable model capable of identifying potentially fraudulent transactions.

## ⚙️ Features

- Loads and preprocesses credit card transaction data
- Performs feature engineering (e.g., age calculation from DOB)
- One-hot encodes categorical variables
- Scales numeric features using `StandardScaler`
- Balances the dataset using `SMOTE`
- Trains a **Gradient Boosting Classifier**
- Evaluates the model with **ROC AUC Score** and **Classification Report**
- Provides an **interactive CLI interface** for real-time transaction testing

---

## 📂 Dataset

The dataset used is available on Kaggle:

🔗 **[Credit Card Fraud Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/kelvinkelue/credit-card-fraud-prediction)**

Make sure to download `Credit_card_fraud.csv` from the above link and place it in your project directory.

---

## 🧪 Model Performance

After training the model on 10,000 sampled records:
- Balanced using SMOTE to handle class imbalance
- Evaluated using test set with:
  - **Classification Report** (precision, recall, f1-score)
  - **ROC AUC Score**

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- StandardScaler
- GradientBoostingClassifier

---
