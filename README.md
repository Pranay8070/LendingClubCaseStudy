# Lending Club
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

- We will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The ojbecive of this exercise is to help Lending Club in reducing their financial risk when approving loan applications. Charged Off loans are the biggest contributor to these losses.

The company wants to understand the patterns in a loan application which can predict whether a borrower will be able to repay the loan or will they default.

We have been given access to existing loan application data with a wide range of information available about the loans and the borroweres. We need to use this data and help Lending Club make informed decisions when sanctioning risky loans.


## Conclusions
1.	Loan Grade
i.	Grade B, C and D have the largest contribution in defaulted loans. LC needs better guidelines and assessments for grading the loans.
ii.	There isn't a clear pattern for sub-grades. LC needs a better framework to categories the loans.
2.	Employment Experience
i.	Loans given to borrowers with 10+ Years of expirience are at a higher risk of being charged off.
ii.	There is a big jump (3%-24%) in loan defaults from 9 to 10+ Years, suggesting that granular details are needed for 10+ years expirience category. Currently 10+ holds everyone with more than 9 years of experience.
3.	Loan Term - More than 50% of defaulted loans are taken for lower term, LC should consider the term decisions as small term loans tend to have higher installments which can impact repayment capacity.
4.	Trend -
i.	There is an upward trend in loan defaults since 2007 with 2011 seeing maximum number of defaulted loans.
ii.	Most of the defaulted loans are approved around end of year, this co-incides with the holiday seasons.
5.	Credit History - Long credit history doesn't necesarily means the ability or repayment.
6.	Home Ownership - Customers with Rented and Mortgaged homes make up for 90% of charged off loans. LC need to ensure the borrower with Rented o Mortgaged accomodations have enough surplus to meet their EMI requirement.
7.	Income Verification - Verified income loans makes up for over 60% of defaulted loans. LC need to ensure that income verification process is more robust and take other factors into account such as DTI ratio, existing commitments etc.
8.	Purpose - Customer who take loans for debt_consolidation are at a higher risk of defaulting as they are already under financial pressure and might not meet the commitment.
9.	Geography - Most of the defaulted borrowers come from high GDP states such as California, Florida, New York, Texas and New Jersey. LC needs to take local trends into account when sanctioning loans.
10.	Past Credit History -
i.	surprisingly, credit hungry customers (With high number of credit inquiries) are less likely to default.
ii.	Customers with no past public deliquency record or bankruptcy recoreds are 8X more likely to default on loans than the customer with past public records.
11.	Loan Amount - Loans in the range of 5-15K are at higher risk of defaulting. LC can cover their risks by capping the loan amount or by increasing interest.
12.	Interest Rate -
i.	Maximum defaulted loans have int_rate between 10 and 17 percent.
ii.	Surprisingly, loans with higher interest rate >18% have very low default rates. LC can use this to increase int_rate for high risk loans.
13.	Annual Income - Majority of charged off loans are from income range 37K-70K.
14.	Installments - Loans with installments between 75-300 faced issues with repayment. LC can offer longer terms for these loans to reduce installment burden.



## Technologies Used
•	python 
•	matplotlib v3.9.3
•	numpy v1.24.1
•	pandas v1.5.2
•	seaborn v0.13.2


