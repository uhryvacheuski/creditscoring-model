# creditscoring-model
Application of different classification algorithms to model credit score

Data soruce: https://www.kaggle.com/brycecf/give-me-some-credit-dataset

Data set consist of following variables: 

 - SeriousDlqin2yrs - Person experienced 90 days past due delinquency or worse (Target)
 - RevolvingUtilizationOfUnsecuredLines - Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits
 - age - Age of borrower in years
 - NumberOfTime30-59DaysPastDueNotWorse - Number of times borrower has been 30-59 days past due but no worse in the last 2 years.
 - DebtRatio - Monthly debt payments, alimony,living costs divided by monthy gross income
 - MonthlyIncome - Monthly income
 - NumberOfOpenCreditLinesAndLoans - Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards)
 - NumberOfTimes90DaysLate - Number of times borrower has been 90 days or more past due.
 - NumberRealEstateLoansOrLines - Number of mortgage and real estate loans including home equity lines of credit
 - NumberOfTime60-89DaysPastDueNotWorse - Number of times borrower has been 60-89 days past due but no worse in the last 2 years.
 - NumberOfDependents - Number of dependents in family excluding themselves (spouse, children etc.)

Metric: ROC-AUC

Metrics best value: 0.755349

Due to imbalanced data applied undersampling with helps to increase metric value

Tried to apply below algorithms
- Logistic Regression
- KNN
- SVM
- Decision Tree (best)
- Random Forest 
- Gradient Boosting 

