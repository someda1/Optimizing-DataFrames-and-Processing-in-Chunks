# Optimizing-DataFrames-and-Processing-in-Chunks

In this project, we'll practice working with chunked dataframes and optimizing a dataframe's memory usage. We'll be working with financial lending data from Lending Club, a marketplace for personal loans that matches borrowers with investors. You can read more about the marketplace on its website.

The Lending Club's website lists approved loans. Qualified investors can view the borrower's credit score, the purpose of the loan, and other details in the loan applications. Once a lender is ready to back a loan, it selects the amount of money it wants to fund. When the loan amount the borrower requested is fully funded, the borrower receives the money, minus the origination fee that Lending Club charges.

We'll be working with a dataset of loans approved from 2007-2011 (https://bit.ly/3H2XVgC). We've already removed the desc column for you to make our system run more quickly.

If we read in the entire data set, it will consume about 67 megabytes of memory. Let's imagine that we only have 10 megabytes of memory available throughout this project, so you can practice the concepts you learned in the last two lessons.

Tasks

Read in the first five lines from loans_2007.csv (https://bit.ly/3H2XVgC) and look for any data quality issues.

Read in the first 1000 rows from the data set, and calculate the total memory usage for these rows. Increase or decrease the number of rows to converge on a memory usage under five megabytes (to stay on the conservative side).
