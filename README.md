# Lending Club Case Study - EDA
Lending club is a consumer finance company, specializing in lending various type of loans to urban customers
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business
- If the applicant is not likely to repay the loan (likely to default), then approving the loan may lead to financial loss 


## Table of Contents
* Business Case
* EDA - Method Adopted
* Univariate Analysis
* Bivariate Analysis
* Segmented Analysis
* Reccomendations

## General Information
- Objective:
	To find the patterns which influence the applicants to default their loan based on historical transactions
- Scope:
	Accepted loan transaction from the period of 2007 to 2011

## Conclusions
- Grade A borrowers have more chance of making full payments on their loan. Focusing & offering more loans for grade A borrowers can reduce the charge off instances
- Charge off % is higher for the loans borrowed for small business, renewable energy & education purposes. Extra scrutiny can be deployed on loan processing process in these segments
- Loan term of 60 months has 22% probability of being charged off against 11% for the term of 36 months. Loan tenure can be further reviewed & reduced in the possible cases
- Revolving line utilization rate is higher for defaulted borrowers. So, it can be set as an additional criteria while approving loans
- The loans with interest rate <= 10% have less probability to be not paid. Interest rate ranges can be reviewed & reduced to best fit the customers to avoid the charge offs

## Technologies Used
- pandas- version 1.0.1
- numpy- version 1.18.1
- seaborn- version 0.11.2
- matplotlib- version 3.1.3

## Contact
Created by [@sindhus123] - feel free to contact me!