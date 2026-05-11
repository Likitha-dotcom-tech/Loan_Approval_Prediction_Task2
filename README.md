# Loan Approval Prediction

## Overview
This project is a Machine Learning based Loan Approval Prediction system developed as part of the internship task at Alfido Tech. The main objective of this project is to predict whether a loan application will be approved or rejected based on applicant details.

## Project Objective
The goal of this project is to:
- Analyze loan applicant data
- Perform data preprocessing
- Handle missing values and class imbalance
- Train machine learning models
- Compare model performance
- Predict loan approval status

## Dataset
Dataset used:
https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study

The dataset contains information such as:
- Gender
- Marital Status
- Education
- Applicant Income
- Loan Amount
- Credit History
- Property Area
- Loan Status

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Pickle

## Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test splitting

### 2. Handling Class Imbalance
- SMOTE technique used for balancing classes

### 3. Machine Learning Models
- Logistic Regression
- Random Forest Classifier

### 4. Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Results
Random Forest performed better compared to Logistic Regression with improved prediction accuracy and ROC-AUC score.

Key findings:
- Credit history strongly affects loan approval
- Applicants with stable income have higher approval chances
- Proper preprocessing improves model performance significantly

## Files Included
Loan-Approval-Prediction/
│
├── dataset/
├── notebook/
├── images/
├── report/
├── README.md
└── requirements.txt

## Future Improvements
- Hyperparameter tuning
- Web application deployment
- Advanced ensemble models
- Real-time prediction system

## Internship Details
Company: Alfido Tech
Task: Loan Approval Prediction
Domain: Machine Learning / Data Science

## Author
D Likitha Sai
