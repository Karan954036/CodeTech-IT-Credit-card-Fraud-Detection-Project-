# CodeTech-IT-Credit-card-Fraud-Detection-Project-

Project Title: Credit Card Fraud Detection using Machine Learning
Description
This project aims to detect fraudulent credit card transactions using machine learning techniques. The model leverages various algorithms to identify and prevent fraudulent activities in real-time.

Dataset
Source: Kaggle1

Details: The dataset contains transactions made by European cardholders in September 20231
. It includes both legitimate and fraudulent transactions1
.

Features: PCA-transformed features (V1, V2, ..., V28), Time (Seconds elapsed between each transaction and the first transaction), Amount (Transaction amount), Target variable (Class: 1 for fraudulent transactions, 0 for legitimate ones)2
.

Machine Learning Models Used
Logistic Regression

Random Forest

Neural Networks

Support Vector Machines

XGBoost

Preprocessing Techniques
Handling missing values

Normalizing transaction amounts using StandardScaler

Addressing data imbalance with resampling techniques

Methodology
Data Preprocessing: Handle missing values, normalize transaction amounts, and address data imbalance2
.

Model Training: Train various machine learning models on the preprocessed dataset.

Model Evaluation: Evaluate models based on metrics like Precision, Recall, Accuracy, and F1 Score2
.

Model Deployment: Deploy the best-performing model as a web service for real-time fraud detection.

Requirements
Libraries: numpy, pandas, scikit-learn, imblearn, xgboost, matplotlib2

Installation: Install required libraries using pip: pip install numpy pandas scikit-learn imblearn xgboost matplotlib
