# Loan Data Exploration
## by Awurigwe Joseph


## Dataset

The dataset comprised of 81 features and attributes of 113,937 loans. The features included in my analysis were Term, LoanStatus, BorrowerRate, BorrowerAPR, ProsperRating (numeric), ProsperScore, ListingCategory (numeric), Occupation, EmploymentStatus, IsBorrowerHomeowner, DelinquenciesLast7Years, IncomeRange, LoanOriginalAmount, LoanOriginationDate, Recommendations


## Summary of Findings
- The  Prosper Rating assigned at the time the listing was created: 0 - N/A, 1 - HR, 2 - E, 3 - D, 4 - C, 5 - B, 6 - A, 7 - AA.  Applicable for loans originated after July 2009.

- The distribution of the Prosper Rating follows a normal distribution and is Unimodal
- The `4` rating is the most common rating given to customers with the `1` and `7` the least.
- the distribution the borrower rate has a multimodal distribution, The variable peaked at the 3.15-3.20 bin. Which means that the majority of the borrower rates are in that region
- The Loan Amounts that were above 26000 were Completed
- There's a strong correlation between the borrowerRate and the Ratings
- People with Higher ratings get lesser BorrowerRate and otherwise
- in every instance, the BorrowerRate of the defaulters were always greater than that of those that completed their loan

## Key Insights for Presentation

### Univariate Insights
- The number in unemployed category is small, so we can deduce that it's hard for unemployed people to get loans at the Lending Facility
- The Prosper Numeric Rating of '7' is the highest and it's also given to the least number of people
- The Interest Rate at Prosper's ranges from 4% to 36% with the mean around 20%, the most common rate being between 3.15 and 3.20

### Bivariate Insights
- The Lowest Prosper Ratings were associated with those who were Not Employed, Self-employed and others.
- There wasn't much correlation between the Loan amount and Loan Status
- The '7' Rating has the least number of defaulters 

### Multivariate Insights
- There was a clear indication that the income range has little or no effect on the borrowerRate.
- The Borrowers' rate of those that defaulted was always greater than those that completed their Loan