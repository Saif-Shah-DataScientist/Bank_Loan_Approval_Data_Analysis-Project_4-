# Bank Loan Approval Data Analysis

## Project Overview
This project analyzes bank loan application data to understand the key factors that influence whether a loan is approved or rejected. The goal is to provide data-driven insights that help banks improve their credit risk assessment and lending strategies.

## Objectives
- Identify major predictors of loan approval  
- Examine the impact of credit history, income, and employment type  
- Analyze how loan amount and term affect approval outcomes  
- Provide actionable insights to improve approval strategies  

## Dataset
- File: Bank_Loan_Approval.csv (or similar)
- Source: Kaggle or other open data sources
- Key Columns: Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data loading and inspection  
2. Data cleaning (handling missing values, correcting data types, removing duplicates)  
3. Feature engineering (creating Total_Income, Loan-to-Income ratio)  
4. Exploratory Data Analysis (EDA)  
5. Visualization of income distribution, loan status patterns, and approval rates  
6. Insights and business recommendations  

## Key Insights
- **Credit history is the strongest predictor of loan approval.** Applicants with a positive credit record have far higher approval rates.  
- **Total household income matters more than individual income.** Combining applicant and co-applicant income improves prediction accuracy.  
- **Self-employed applicants have lower approval rates**, likely due to perceived income instability.  
- **Loan amount and term interact**, where higher loan sizes or longer terms reduce approval chances unless supported by strong income and credit history.  
- **Property area influences approval rates**, suggesting regional policy or risk differences.

## Business Recommendations
- Prioritize applicants with verified positive credit history for faster processing.  
- Use total household income as a key metric in risk assessment models.  
- Consider flexible credit evaluation models for self-employed applicants.  
- Review loan-to-income and loan-term ratios to align approval thresholds with financial risk.  
- Re-examine lending policies across property areas to ensure fair approval criteria.  

## Requirements
To install the required libraries, run:
