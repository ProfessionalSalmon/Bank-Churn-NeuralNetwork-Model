# Bank Churn Modeling

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

### 2. Exploratory Data Analysis (EDA)
- Understanding data distributions
- Identifying correlations
- Visualizing important features

### 3. Model Selection & Training
- Tried multiple machine learning models (e.g., Logistic Regression, Decision Trees, Random Forest, Neural Networks)
- Tuned hyperparameters for better performance

### 4. Model Evaluation
- Measured performance using **accuracy, precision, recall, F1-score, and AUC-ROC**
- Compared different models to select the best one

### 5. Deployment & Interpretation
- Explained key insights from the model
- Suggested business strategies based on predictions

## Results & Insights

### Key Findings

- The model with the best **recall** score was chosen to minimize false negatives and effectively identify potential churners.
- Older customers tend to have a higher churn rate, with age being one of the most influential factors.
- Customers with lower account balances and those who own fewer products are more likely to churn, as these features also show moderate importance.
- Inactive members and individuals with a low credit score exhibit a higher likelihood of churning, though these factors have less influence compared to age and balance.

### Business Implications

- Retention strategies should focus on **re-engaging inactive members** through personalized offers.
- Encouraging customers to use multiple products may help reduce churn rates.
- Special attention should be given to **high-risk customers (low balance & high age group)** through targeted retention campaigns.