# Loan Data From Prosper Exploration
## by Madaki Fatsen Timon


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, 
including loan amount, borrower rate (or interest rate), current loan status, 
borrower income, and many others. The dataset can be located 
[on](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)  and the data dictionary to understand the 81 variables can be found 
[here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) 


## Summary of Findings

> I observed that there was a relationship between employment status and loan status. A countplot with Loan status on the x-axis and hue of employment status was plot. It was observed that the employed under the current and completed loan status has a very high count in proportion to the other employment status.
There is a negative correlation between Borrower APR or Rate and Loan Original Amount. A scatter plot was plotted with Loan original amount on the x-axis and Borrower APR or Rate on the y-axis.
Also, there a positive correlation between  Borrower Rate and loan term. The higher the duration of the loan the more the borrower Rate value. This was depicted in the violin plot, with term on the horizontal axis and Borrower Rate on the vertical axis.
In looking at the factor that checks for differences in the loan, attention was placed on the Loan original amount and term of the loan. A multivariate scatter plot with loan original amount on the x-axis, Borrower APR and term as the col parameter, showed clearly that larger amounts of loans were collected with higher loan duration. High term proportionate larger amounts of LoanOriginalAmount.


## Key Insights for Presentation

> Firstly, focus was layed on employment status as it influence loan status. Few of the employment status was picked by applying the isin funtion on the dataset, hence a new column (EmploymentType) was created. And my plot was made. Secondly, to find factors affecting Borrower Rate/APR two different scatter plot was plotted; on both plot the Loan original amount was on the x-axis, Borrower Rate was used on the x-axis for one plot and Borrower APR was also used on the x-axis for other plot. Thirdly, to find the relationship between Borrower Rate and Loan Term, a violin plot was plotted with Borrowers rate on the y-axis and Loan term on the x-axis. Lastly, we seek to relay the relationship between Loan Original amount and loan term, a multivariate scatter plot was plotted setting transparency to 1/20.
