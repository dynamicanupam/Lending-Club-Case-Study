# Lending Club Case Study

## The Context

When a person applies for a loan, there are two types of decisions that could be taken by the company:

- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    -  Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

![image](https://github.com/dynamicanupam/Lending-Club-Case-Study/assets/61014822/08456ba6-3140-4337-a71a-8145899f476a)


## Business Objectives

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters.'

So in this case study, we"ll understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of "default". The company can utilise this knowledge for its portfolio and risk assessment.

## Soluation Approach 

Step 1: Data Understanding, Cleaning and Manipulating
-  Checking percentage of missing values
-  Removing the columns with high percentage of missing values(>50%)
-  Identify and remove single valued columns
-  Identify and remove least signifiance columns
-  Imputing the missing values
-  Checking the data type of columns and fixing the incorrect data types and format
-  Treating Outliers

Step 2: Exploratory Data Analysis
-  Univariate Analysis
-  Segemented Univariate Analysis
-  Bivaraiate Analysis
-  Multivariate Analysis

Step 3: Recommendations
