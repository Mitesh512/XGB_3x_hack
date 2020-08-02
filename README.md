# XGB_3x_hack
Steps for Data preparation 


City variable dropped because of too many categories
DOB converted to Age | DOB dropped
EMI_Loan_Submitted_Missing created which is 1 if EMI_Loan_Submitted was missing else 0 | Original variable EMI_Loan_Submitted dropped
EmployerName dropped because of too many categories
Existing_EMI imputed with 0 (median) since only 111 values were missing
Interest_Rate_Missing created which is 1 if Interest_Rate was missing else 0 | Original variable Interest_Rate dropped
Lead_Creation_Date dropped because made little intuitive impact on outcome
Loan_Amount_Applied, Loan_Tenure_Applied imputed with median values
Loan_Amount_Submitted_Missing created which is 1 if Loan_Amount_Submitted was missing else 0 | Original variable Loan_Amount_Submitted dropped
Loan_Tenure_Submitted_Missing created which is 1 if Loan_Tenure_Submitted was missing else 0 | Original variable Loan_Tenure_Submitted dropped
LoggedIn, Salary_Account dropped
Processing_Fee_Missing created which is 1 if Processing_Fee was missing else 0 | Original variable Processing_Fee dropped
Source – top 2 kept as is and all others combined into different category
Numerical and One-Hot-Coding performed
