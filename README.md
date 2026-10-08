# Task 5 - Credit Card Fraud Detection

## 📌 Project Overview

This project is part of my **CodSoft Data Science Internship**.

The objective of this project is to build a machine learning model that can identify whether a credit card transaction is **genuine or fraudulent**.

The project focuses on data preprocessing, normalization, handling class imbalance, and classification using Machine Learning.

## 🎯 Objective

- Identify fraudulent credit card transactions.
- Preprocess and normalize transaction data.
- Handle the imbalance between genuine and fraudulent transactions.
- Train a machine learning classification model.
- Evaluate the model using suitable performance metrics.

## 📊 Dataset

The project uses the **Credit Card Fraud Detection** dataset from Kaggle.

The dataset contains credit card transactions with a target column called `Class`.

- `0` → Genuine transaction
- `1` → Fraudulent transaction

The dataset contains a highly imbalanced distribution of genuine and fraudulent transactions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Google Colab

## 🔍 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check missing values
5. Analyze genuine and fraudulent transactions
6. Preprocess the data
7. Split the dataset into training and testing sets
8. Normalize the features using StandardScaler
9. Handle class imbalance using SMOTE
10. Train a Logistic Regression model
11. Make predictions
12. Evaluate the model
13. Generate a confusion matrix

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression was used as the classification algorithm to predict whether a transaction is genuine or fraudulent.

## ⚖️ Handling Class Imbalance

The dataset contains significantly fewer fraudulent transactions than genuine transactions.

To address this class imbalance, **SMOTE (Synthetic Minority Over-sampling Technique)** was applied to the training data.

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help evaluate how effectively the model identifies fraudulent transactions.

## 📁 Project File

`Credit_Card_Fraud_Detection.ipynb`

## 👩‍💻 Internship

**CodSoft Data Science Internship**

**Task 5: Credit Card Fraud Detection**
