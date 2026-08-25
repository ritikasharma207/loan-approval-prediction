# Loan Approval Prediction Using Support Vector Machines

## 📌 Project Overview

This project uses Machine Learning to predict whether a loan application will be **approved or not approved** based on applicant and financial information.

A **Support Vector Machine (SVM)** with a **linear kernel** is used for classification.

## 🎯 Objective

The objective is to build a Machine Learning model that can:

- Process loan application data
- Train an SVM classification model
- Predict loan approval status
- Evaluate model performance

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## 📊 Dataset

The dataset contains information about loan applicants, including:

- Gender
- Married
- Dependents
- Education
- Applicant Income
- Co-applicant Income
- Loan Amount
- Credit History
- Property Area
- Loan Status

`Loan_Status` is the target variable:

- `1` → Approved
- `0` → Not Approved

## ⚙️ Project Workflow

1. **Data Collection** – Load and inspect the loan dataset.
2. **Data Preprocessing** – Handle missing values and convert categorical data into numerical values.
3. **Data Visualization** – Analyze relationships between applicant features and loan status.
4. **Train-Test Split** – Split the data into 90% training and 10% testing data.
5. **Model Training** – Train a Support Vector Machine using a linear kernel.
6. **Model Evaluation** – Calculate training and testing accuracy.
7. **Final Prediction** – Predict the loan status of an applicant.

## 📈 Results

| Metric | Accuracy |
|---|---:|
| Training Accuracy | **≈ 82%** |
| Test Accuracy | **≈ 78%** |

## 📁 Project Files

```text
Loan-Approval-Prediction/
│
├── Loan_Prediction.ipynb
├── Loan_prediction.py
├── loan.csv
├── README.md
└── docs/
    ├── Loan_Approval_Prediction_Project_Report.docx
    ├── Loan Approval.pptx
    └── Loan_Screenshots.docx
```
