# Loan Eligibility Prediction Project
## Overview:
This project focuses on predicting the loan eligibility of customers in a bank using machine learning techniques. The goal is to assist the bank in automating the loan approval process by analyzing various customer features and determining their eligibility for a loan.

## Project Structure:
### Data:
The project utilizes a dataset containing customer information that includes:
- Loan_ID : Unique Loan ID

- Gender : Male/ Female

- Married : Applicant married (Y/N)

- Dependents : Number of dependents

- Education : Applicant Education (Graduate/ Under Graduate) Self_Employed : Self employed (Y/N)

- ApplicantIncome : Applicant income

- CoapplicantIncome : Coapplicant income

- LoanAmount : Loan amount in thousands of dollars

- Loan_Amount_Term : Term of loan in months

- Credit_History : Credit history meets guidelines yes or no

- Property_Area : Urban/ Semi Urban/ Rural Loan_Status : Loan approved (Y/N) this is the target variable

### Notebooks:
`loan_prediction.ipynb`
- Contains data cleaning and preprocessing steps.
- Explores the dataset to gain insights.
- Implements machine learning models for loan eligibility prediction.
- Evaluates the performance of the trained models.

### Models:
Includes trained machine learning models for loan eligibility prediction.
### Results:
Contains the results and evaluation metrics of the models.

## Instructions:
### Data Preparation:
Ensure the dataset is in the correct format and contains all necessary features.
Run Data_Preprocessing.ipynb to clean and preprocess the data.

### Exploratory Data Analysis:
Explore Exploratory_Data_Analysis.ipynb to understand the dataset better.

### Model Training:
Execute Model_Training.ipynb to train machine learning models for loan eligibility prediction.

### Model Evaluation:
Evaluate the performance of the trained models.

## Dependencies:

Python 3.x
Jupyter Notebook
Pandas
NumPy
Scikit-learn

## Conclusion:
This project aims to provide a predictive model that can assist the bank in making informed decisions regarding loan approvals. By leveraging machine learning techniques, the bank can streamline its loan approval process and improve efficiency.
