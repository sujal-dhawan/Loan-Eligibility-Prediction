# Loan Eligibility Prediction using Machine Learning

## Overview
This project involves developing a machine learning model to predict loan eligibility based on various factors like gender, marital status, education, applicant income, credit history, and others. The dataset used contains features that impact loan approval decisions.

## Dataset
The dataset includes:
- `Loan_ID`
- `Gender`
- `Married`
- `Dependents`
- `Education`
- `Self_Employed`
- `ApplicantIncome`
- `CoapplicantIncome`
- `LoanAmount`
- `Loan_Amount_Term`
- `Credit_History`
- `Property_Area`
- `Loan_Status`

## Steps Followed
- **Data Preprocessing**: Missing values were handled and categorical variables were encoded.
- **Model Training**: We used Random Forest and Logistic Regression models.
- **Evaluation**: The models were evaluated using ROC AUC scores, confusion matrix, and classification reports.
- **Visualization**: Various visualizations such as pie charts, histograms, and boxplots were used to understand the dataset.

## Models Used
- Random Forest
- Logistic Regression

## Evaluation Metrics
- ROC AUC Score
- Confusion Matrix
- Precision, Recall, F1-Score

## How to Run
1. Download the dataset and place it in the `dataset` folder.
2. Run the notebook and ensure all dependencies are installed.

## Requirements
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

## Conclusion
The project demonstrates the process of handling imbalanced data, model training, and evaluation for loan eligibility prediction. It also includes essential data visualizations to better understand the impact of various factors on loan eligibility.
