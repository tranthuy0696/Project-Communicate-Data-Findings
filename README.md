# (Loan Data from Prosper)
## by (ThuyTTT19@fpt.cpm)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See the data dictionary below to understand the dataset's variables.


## Summary of Findings

In my bivariate analysis, the initial heatmap visualization revealed a notable negative correlation between the borrower's APR and the original loan amount. This suggests that as the size of the loan increases, the APR tends to decrease. Additionally, there is a negative correlation between the Debt-to-Income Ratio and Stated Monthly Income, indicating that as one’s income rises, their debt-to-income ratio decreases. Conversely, the correlation between the original loan amount and stated monthly income is positive, which is logical since higher income generally allows for higher loan amounts.

Further analysis through various plotting techniques highlighted the significant impact of a borrower's rating on APR. Improved ratings are associated with substantially lower APRs, while less favorable statuses—such as ChargedOff, Past Due, and Defaulted—correlate with higher APRs. This underscores the importance of credit ratings in determining borrowing costs.

In the multivariate exploration, I examined how a borrower’s rating influences the relationship between loan amount and APR. It appears that this relationship becomes increasingly positive and stronger as the borrower’s rating improves. Interestingly, the loan term does not notably affect this relationship. However, when analyzing the term's impact on APR across different ratings, I found that while APR generally decreases with longer loan terms for lower ratings, it increases for borrowers with ratings B-AA. This divergence suggests that for higher ratings, longer terms might be associated with more personalized or customized lending conditions.


## Key Insights for Presentation

For the presentation, my main focus will be on analyzing the features that potentially influence Borrower APR. I will explore both categorical and numeric variables to understand their impact. The categorical variables under consideration include 'LoanStatus', 'IncomeVerifiable', 'EmploymentStatus', 'Term', and 'ProsperRating (Alpha)'. For numeric variables, I will delve into 'BorrowerAPR', 'StatedMonthlyIncome', 'LoanOriginalAmount', and 'DebtToIncomeRatio'. My analysis will examine various relationships, such as how APR correlates with loan amount and how it varies across different ratings.
# Project-Communicate-Data-Findings
