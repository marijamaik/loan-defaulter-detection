# Loan Default Prediction with Machine Learning Classification Models

Developed predictive models that help banks minimize loan default risk, enhance decision-making, reduce financial losses, and ensure regulatory compliance.

## Overview  
This project focuses on building a machine learning classification model to predict loan defaulters, allowing banks to mitigate financial risks and improve lending strategies. By leveraging key borrower attributes, the model identifies high-risk applicants and supports responsible lending practices.

## Objectives  
- Accurately predict loan defaulters to minimise default risk.  
- Improve loan approval decisions while ensuring compliance with lending regulations.  
- Optimise model performance with feature selection, tuning, and evaluation.  

## Data & Methodology  
- **Data Analysis**: Univariate, bivariate, and multivariate analysis to understand key patterns.  
- **Preprocessing**: Handling missing values, treating outliers, and scaling features.  
- **Models Used**: Logistic Regression, Decision Tree, Random Forest (with tuning via GridSearchCV).  
- **Evaluation Metric**: Prioritised recall to maximize defaulter identification and minimise financial risk.  

## Key Findings  
- 20% of applicants default on their loans, highlighting a significant class imbalance.  
- Important features include **debt-to-income ratio, number of delinquent credit lines, and credit inquiry age**.  
- **Tuned Decision Tree Model** was selected for its high recall (76%) in identifying defaulters.  

## Next Steps  
- Further fine-tuning to improve recall and prevent overfitting.  
- Monitoring model performance post-deployment.  
- Scaling the solution for larger datasets.  

## Tech Stack  
- **Programming Language**: Python  
- **Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
