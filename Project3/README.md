# Diamonds Data Exploration

## Dataset

The dataset has 113,937 loan entries for people across different states, occupation and income range. 81 variables were measured on each loan including loan amount, interest rate, debt to income ratio, and many more. The dataset can be found in the Udacity 
repository https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000,
with feature documentation available [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).


## Summary of Findings

In the exploration, I observed that majority of Prosper loans are currently running and being serviced appropriately but significant percentage of the loans are also chargedoff and defaulted - 14.9% of booked loans have gone bad.
More than 50% of booked loans went to middle income earners when related to income range defined in the dataset and most of them received loans less than $10,000 at a relatively high interest rate. Few unemployed customers and some without declared income also managed to secure some loan facilities with Prosper.
I verified the relationship between interest rate, customer rating and loan amount. Majority of people that enjoyed low interest rate and can obtain high loan amount have Prosper rating of either AA, A, or B which are the top 3 ratings available to customers.


## Key Insights for Presentation

For the presentation, I focus on the Prosper loan distribution that shows majority of the loans currently good/in-service and a significant portion marked as bad loans. Afterwards, I highlighted majority of Prosper customers inline with the income range distribution of the dataset and touch on the low amount but relatively high interest rate of the loans offered to this group. Finally, I establish relationship between variables: BorrowerRate, LoanOriginalAmount, and ProsperScore.