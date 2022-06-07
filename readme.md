# Communicate Data Findings
## by Mahmoud Medhat Amir
## Preliminary Wrangling

This project is divided into two parts >

> In the first part, we will do exploratory data analysis on a  prosper loan dataset  using Python data science and data visualization .The visu

> In the second part, We will take our important findings from exploration  and communicate  them to through an explanatory analysis. 

## Dataset

> Original dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate , current loan status, borrower income, and many others.

## Data Assessing and Cleaning

> 1. choose subset of columns that are important to decrease the large number of features
> 2. drop duplicated rows 
> 3. convert ListingCreationDate to datetime

## Summary of Findings

> I'm interested in knowing what features are best for predicting  the status of the loan .

> January has the highest number of loans . There is increasing in loans listed with each passing year

> The distribution of APR looks multimodal. A small peak centered at 0.1, a large peak centered at 0.2. There is also a small peak centered 0.3. Additionally, there is a sharp peak between 0.35 and 0.36. Only very few loans have APR greater than 0.43.
> The distripution shows that most of borrowers go for 1:4 debt to income which makes sense.
>The graph of prosperRating is shown as a normal distribution, C has the largest no of counts.

> Here is the answer for the question asked ,As we can see that the debt to income ratio for the completed loans is smaller than for the defaulted loans which makes sense , as the borrowers with smaller debt to income ratio are more able to complete their loans.
> The borrower APR decreases with  better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR.


> The borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the increase of borrow term.
> The borrower APR is one the factors affecting the loan status , as you see in the graph the borrower APR for defaulted loans is higher than borrower APR in the completed loans.
> 
> This distribution is divided into two parts , The borrower APR decreases with the no of terms with rating from HR-C but in the other part from C to AA the borrower APR increases with no of terms.

## Key Insights for Presentation

> January has the highest number of loans . There is increasing in loans listed with each passing year

> The distribution of APR looks multimodal. A small peak centered at 0.1, a large peak centered at 0.2. There is also a small peak centered 0.3. Additionally, there is a sharp peak between 0.35 and 0.36. Only very few loans have APR greater than 0.43.
> The distripution shows that most of borrowers go for 1:4 debt to income which makes sense.
>The graph of prosperRating is shown as a normal distribution, C has the largest no of counts.

> Here is the answer for the question asked ,As we can see that the debt to income ratio for the completed loans is smaller than for the defaulted loans which makes sense , as the borrowers with smaller debt to income ratio are more able to complete their loans.
> The borrower APR decreases with  better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR.


> The borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the increase of borrow term.
> The borrower APR is one the factors affecting the loan status , as you see in the graph the borrower APR for defaulted loans is higher than borrower APR in the completed loans.
> 
> This distribution is divided into two parts , The borrower APR decreases with the no of terms with rating from HR-C but in the other part from C to AA the borrower APR increases with no of terms.

