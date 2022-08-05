# Prosper Loan Data Exploration
## by Olumide Olaoye


## Dataset

The dataset consisted of Borrower APRs and attributes of 113,937 loans. The attributes included Loan Original Amount, borrower's Prosper Rating (Alpha), loan term (Term), borrower's Stated Monthly Income, as well as many other features such as borrower's Employment Status, Debt To Income Ratio, Current Loan Status, etc. The dataset can be found at https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000, with feature documentation available at https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554484977407000


## Summary of Findings

In my exploration of the dataset, I discovered that:

- The Loan Original Amount increases with better Prosper Rating (Alpha) score.

- The Borrower APR decreases with better ProsperRating (Alpha) score.

- Interestingly, the relationship between Borrower APR and Loan Original Amount turns from negative to slightly positive when the Prosper Ratings are increased from HR to A or better. This may be because people with A or AA ratings tend to borrow more money, increasing APR could prevent them from borrowing even more and maximize the profit. But people with lower ratings tend to borrow less money, decreasing APR could encourage them to borrow more.

- Outside of the main variables of interest, I found that the Loan Original Amount is positively correlated to the Stated Monthly Income. This means that the more disposable monthly income a person has, the more loans he can afford to give out. It also shows that borrowers with better rating also have larger monthly income and loan amount.

- There is an interaction between Prosper Rating (alpha) and Term. The Employment Status variable do not have enough data on Part-time, Retired and Not-employed borrowers to show its interaction with Term and ProsperRating variables.

- Also, there is an interaction between Term and ProsperRating (Alpha). By proportion, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers.

- The loan amount is also increased with the increase of loan term. I also found that borrowers with better Prosper Ratings have larger Stated Monthly Income and Loan Original Amount. 

- Employed, self-employed and Full-time borrowers have more Stated Monthly Income and Loan Original Amount than Part-time, Retired and Not-employed borrowers. There is an interaction between categorical term and Prosper Rating features. 

- For Loan Original Amount, there is an interaction between Term and Prosper Rating. With better Prosper Rating, the Loan Original Amount of all three terms increases, the increase amplitude of Loan Original Amount between Terms also becomes larger.


## Key Insights for Presentation

For the presentation, based on my hypothesis, I focused mainly on features that could affect the Borrower APR, which are Loan Original Amount, and Prosper Rating. 

First, I began by showing the distribution of Borrower APR and Loan Original amount variables. 

Second, I showed the relationship between Borrower APR and Loan Original Amount, as well as the relationship between Borrower APR and Prosper Rating. 

Lastly, I investigated the effect of Prosper Rating on relationship between Borrower APR and Loan Original Amount, as well as the effect of Prosper Rating on relationship between Borrower APR and Term.