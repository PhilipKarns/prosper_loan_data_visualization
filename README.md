# prosper_loan_data_visualization
Data visualization of loan analysis from Prosper

## Dataset
The data consists of information regarding 113,937 Prosper loans, and 81 variables
for each loan including borrower interest rate, credit score, homeownership status,
and risk score. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000),
and a data dictionary to explain loan variables [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000).

#Summary of Findings
In the exploration I found that there was a strong relationship between a borrower's 
credit score and their loan interest rate. There is a negative correlation between them,
because as credit scores increase, loan interest rates decrease, and vice versa. I expected
borrowers that utilized a high percentage of their avaialble credit to have higher credit scores,
though analysis between those two variables only showed a slight positive correlation. Other 
variables that did have an effect on borrower interest rates and credit scores were Prosper Scores
, which is the risk score prosper assigns to a borrower, and homeownership status. Riskier borrowers
had higher interest rates and credit scores, and homeowners had lower interest rates and credit scores.

Other variables I reviewed included the state the borrower lived in, borrower employment status, and loan
type. California had the large majority of the loans, and most of those loans were for debt consolidation,
which was interesting because it's also one of the most expensive states to live in. Employed borrowers did 
typically have lower interest rates than non-employed borrowers, and full-time employees had the best rates.
A majority of the loans in the dataset were for Debt Consolidation, and it was interesting to see that those
loans were taken out by people with both good and bad credit, which made it clear that debt consolidation
isn't mainly done by people in financial distress.

 