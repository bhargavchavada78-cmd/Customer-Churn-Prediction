# Customer Churn Prediction

This project builds a Machine Learning model to predict whether a customer will leave a bank (churn) or continue using the bank's services.

Customer churn prediction helps businesses identify customers who are likely to leave so they can take actions to retain them.

---

## Project Overview

Customer churn occurs when a customer stops using a company's product or service. In this project, we use historical customer data such as credit score, age, balance, and activity status to train a machine learning model that predicts whether a customer will churn.

---

## Dataset

Dataset used: **Bank Customer Churn Prediction**

Features in the dataset include:

- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

Target Variable:

Exited  
0 → Customer stays  
1 → Customer leaves (Churn)

Dataset Source:  
https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Machine Learning Algorithms Used

- Logistic Regression
- Random Forest Classifier

These algorithms were used to classify whether a customer will churn or not.

---

## Project Workflow

1. Import Libraries  
2. Load Dataset  
3. Data Exploration  
4. Data Preprocessing  
5. Feature Selection  
6. Train-Test Split  
7. Feature Scaling  
8. Model Training  
9. Model Evaluation  
10. Prediction on New Data

---

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Random Forest produced better performance compared to Logistic Regression.

Model Accuracy: ~85% (approx)

---

## Project Structure
