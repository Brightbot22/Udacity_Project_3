# Prosper Loan Dataset Exploration Report
## by Bright Obot


## Dataset

> The dataset was downloaded from a Link provided in the Udacity classroom. The data set contained 113,937 loans with 81 variables on each loan. The Variables in the dataset included loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The first step was to download ProsperLoanDataset.csv into a directory created specifially for my project, then I loaded my dataset into my notebook form this directory.The next step was data cleaning (after assessing the dataset) to prepare my data for exploration. Variables with wrong datatype like LoanOriginationDate was corrected to suit our exploration. Also column names not in standard form were corrected. All comumns and variables we will ot use for our exploration and analysis were removed from the dataset.


## Summary of Findings

> The main main variables of interest is the Loan Status. Visualization on this variable showed that income was concentrated between 25,000 and 49,999 USD($). Also the distribution of Borrowers interest Rate (BorrowerRate) was skewed to the right, and most of the borrowers fell within the higher interest rate loans. The Visualization for Loan status also explained that a  larger percentage of loans were either in current or completed status. We observed that about 50% and 34% of all Prosper loans are in Current Status and completed status respectively. Also about 11% and 4% of Prosper's loans were charged off and defaulted respectively. None of the loans were past due.

> The Loan Original Amount bar standard plot showed that the Loan orginal amount had a long-tailed distribution with a lot of loans on the low original amount end, and few on the high original amount end. When this standard bar plot was visualized on a log scale, we saw that the distribution looked bimodal and had peaks around 10000, 20000, 22000, 32000, 34000 and 35000.


## Key Insights for Presentation


> In this project we tried to answer the following questions:

> * What factors affect a loan’s outcome status?
> * What factors affects the borrower’s APR or interest rate?
> * Are there differences between loans depending on how large the original loan amount was?

> The factors we Identified for the first questions weew the amount of money borrowed and the rate of interest on the loans. The Higher the interest rate, and high loan values are likely to be past due. The employment statues vary with the borrowers Apr as seen that most Employed individuals were in current loan status. Also a higher original loan amount will tell how high the loan will be.

> We used the correlation heat mix to investigate the factors that affects the borrower's interest rate. We noticed that credit score had a strong correlation with borrower's interest rate compared to the other features

> looking at the correlation between loan status and the original loan amounts, we can say to some extent that the larger the loan amount, the more chance of being in current loan status. Thus differences between loans have positive relationship on the original loan amount.