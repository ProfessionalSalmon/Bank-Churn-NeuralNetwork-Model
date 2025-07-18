# Bank Churn Prediction by Fully Connected Neural Network

## 🍓Overview
This project predicts customer churn for a bank using FNN-based model. The goal is to identify customers who are likely to leave the bank.

## 🍓Dataset
The dataset used in this project includes:
- **Customer ID**
- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited (Target Variable)**

## 🍓Project Workflow

### 🎀1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- SMOTE Resampling

### 🎀2. Neural Network Model Training
- Assess Training and Validation Loss
- Tune hyperparameters

### 🎀3. Model Evaluation
- Measured performance using **Confusion matrix, Classification report, and PR-AUC**
- The model with the best **recall** score was chosen to minimize false negatives and effectively identify potential churners

![PR-AUC](metrics\PR-AUC.png)
![feature-importance](metrics\feature-importance.png)
