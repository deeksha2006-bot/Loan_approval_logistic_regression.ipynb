🏦 Loan Approval Screening — Logistic Regression

 About the Project

This project predicts loan approval outcomes using Logistic Regression, a machine learning algorithm used for binary classification.

The model classifies loan applications into two classes:

- `0` → Negative / No risk
- `1` → Positive / Risk

💼 This project was completed as part of my LearnDepth Internship.

## 🎯 Objective

The main objective is to build a simple Logistic Regression model and evaluate its performance in predicting loan application outcomes.

## 📊 Dataset

The dataset contains 1,000 loan application records with 6 input features and 1 target variable.

###  Features

- 💰 `income_monthly` – Monthly income
- 📈 `credit_score` – Credit score of the applicant
- 💳 `debt_to_income` – Debt-to-income ratio
- 💼 `employment_years` – Years of employment
- 🏦 `loan_amount` – Requested loan amount
- ⚠️ `prior_defaults` – Previous loan defaults
- 🎯 `target` – Loan outcome/risk class

## ⚙️ Methodology

The following steps were performed:

1. 📥 Loaded the dataset
2. 🔍 Inspected the data
3. 🧹 Checked missing values and duplicates
4. 📊 Checked target class distribution
5. ✂️ Split the data into training and testing sets
6. ⚖️ Standardized features using `StandardScaler`
7. 🤖 Built a Logistic Regression model
8. 🏋️ Trained the model
9. 🔮 Generated predictions
10. 📈 Evaluated model performance
11. 🔲 Analyzed the confusion matrix
12. 🔎 Examined feature coefficients
13. 📉 Plotted the ROC curve

## 📈 Model Evaluation

The model performance was evaluated using:

- ✅ Accuracy
- 🎯 Precision
- 🔄 Recall
- 📊 F1-Score
- 📈 ROC-AUC
- 🔲 Confusion Matrix
- 📉 ROC Curve

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 🤖 Scikit-learn
- 📊 Matplotlib
- 📉 Seaborn
- ☁️ Google Colab

## 📁 Project Files

 text
📦 Loan-Approval-Screening
 ├── 📊 dataset_02_loan_approval_screening.csv
 ├── 📓 Loan_Approval_Logistic_Regression.ipynb
 └── 📖 README.md
