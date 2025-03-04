# Bank Churn Prediction by Fully Connected Neural Network

## Overview
This project focuses on predicting customer churn for a bank using machine learning techniques. The goal is to identify customers who are likely to leave the bank, allowing proactive customer retention strategies.

## Dataset
The dataset used in this project includes various customer attributes such as demographics, account details, and transaction history. Key features include:

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

## Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- SMOTE Resampling

### 2. Neural Network Model Training
- Assess Training and Validation Loss
- Tune hyperparameters

### 4. Model Evaluation
- Measured performance using **Confusion matrix, Classification report, and PR-AUC**
- The model with the best **recall** score was chosen to minimize false negatives and effectively identify potential churners

### 5. Deployment & Interpretation
- Explained key insights from the model
- Suggested business strategies based on predictions
