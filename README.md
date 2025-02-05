# Loan Default Prediction with Machine Learning Classification Models

Developed predictive models that help banks minimize loan default risk, enhance decision-making, reduce financial losses, and ensure regulatory compliance.

## Overview  
This project focuses on building a machine learning classification model to predict loan defaulters, allowing banks to mitigate financial risks and improve lending strategies. By leveraging key borrower attributes, the model identifies high-risk applicants and supports responsible lending practices.

## Objective
The goal is to build a classification model that predicts loan defaulters, helping banks mitigate financial risks and make informed lending decisions while maintaining regulatory compliance.

## Tools and Techniques
### Programming Language: Python 3.8

### Libraries: 
- Data Manipulation: Pandas, NumPy  
- Data Visualisation: Matplotlib, Seaborn  
- Modeling: Scikit-learn (Logistic Regression, Decision Tree, Random Forest, GridSearchCV)  
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score  

### Techniques:
- Handling Missing Values and Outliers  
- Feature Engineering & Selection  
- Train-Test Splitting (70%-30%)  
- Model Tuning (GridSearchCV)  
- Performance Evaluation with a Focus on Recall
- 

## Data Dictionary  
The Home Equity (HMEQ) dataset contains baseline and loan performance information for recent home equity loans. The target variable (BAD) indicates whether an applicant defaulted or was severely delinquent. The dataset consists of 12 input features:  

### Target Variable
- BAD: 1 = Client defaulted on loan, 0 = Loan repaid  

### Loan & Property Information
- LOAN: Amount of loan approved  
- MORTDUE: Amount due on the existing mortgage  
- VALUE: Current value of the property  

### Applicant Information 
- REASON: Purpose of the loan (HomeImp = Home Improvement, DebtCon = Debt Consolidation)  
- JOB: Job type (e.g., Manager, Self-employed, etc.)  
- YOJ: Years at present job  

### Credit History & Risk Indicators  
- DEROG: Number of major derogatory reports (serious delinquencies)  
- DELINQ: Number of delinquent credit lines (past due payments)  
- CLAGE: Age of the oldest credit line (in months)  
- NINQ: Number of recent credit inquiries  
- CLNO: Number of existing credit lines  
- DEBTINC: Debt-to-income ratio (measures borrower’s ability to repay)  
