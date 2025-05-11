# Loan Approval Prediction Project

![image](https://github.com/user-attachments/assets/d3d5d6a3-d75d-418d-b186-2471e25c59c1)

Welcome to the Loan Approval Prediction repository.
This project focuses on developing a machine learning model to predict the approval status of loan applications. By analyzing various applicant attributes, the model aims to assist financial institutions in making informed lending decisions, thereby streamlining the loan approval process and enhancing customer service.

## Objective

To build a predictive model that accurately determines whether a loan application should be approved, based on key applicant information. This tool is intended to aid banks in automating the loan approval process, reducing manual workload, and minimizing the risk of default.

##  Dataset Description

The dataset comprises of 599 rows and 13 columns.I have pre-processed the data to handle missing values, outliers, and inconsistencies.
The dataset comprises 13 features collected from historical loan applications:

1. **Loan_ID**: Unique identifier for each loan application  
2. **Gender**: Applicant's gender (Male/Female)  
3. **Married**: Marital status (Yes/No)  
4. **Dependents**: Number of dependents  
5. **Education**: Education level (Graduate/Not Graduate)  
6. **Self_Employed**: Employment status (Yes/No)  
7. **ApplicantIncome**: Applicant's income  
8. **CoapplicantIncome**: Co-applicant's income  
9. **LoanAmount**: Loan amount (in thousands)  
10. **Loan_Amount_Term**: Loan term (in months)  
11. **Credit_History**: Credit history (1: meets guidelines, 0: does not meet)  
12. **Property_Area**: Area of the property (Urban/Semiurban/Rural)  
13. **Loan_Status**: Loan approval status (Y: Approved, N: Not Approved)

##  Methodology

The project follows a structured approach:

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling  
- **Exploratory Data Analysis (EDA)**: Understanding data distributions and relationships between variables  
- **Model Development**: Implementing classification algorithms such as:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)  
- **Model Evaluation**: Using accuracy, precision, recall, and F1-score to assess model performance

##  Expected Outcomes

- A predictive model that can determine loan approval likelihood  
- Insights into key factors influencing loan approvals  
- Enhanced automation and efficiency for banking loan processes
