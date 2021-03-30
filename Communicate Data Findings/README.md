# Loan Data from Prosper Exploration

## by KexinYao


## Dataset

> There are 113937 loans in the dataset with 81 features.Each loan contains the information on the borrowered's background information and details regarding the loans.This analysis will focus on 12 variables listed below:

Term:The lenggth of the loan expressed in months (category)

LoanStatus: The current status of the loan (category)

BorrowerRate: The Borrower's interest rate for this loan

ProsperScore: A custom risk score built using historical Prosper data.(category)

ListingCategory: The category of the listing that the borrower selected when posting their listing. (category)

EstimatedReturn: The estimated return assigned to the listing at the time it was created.

BorrowerState: The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.(category)

EmploymentStatus: The employment status of the borrower at the time they posted the listing.(category)

IncomeRange: The income range of the borrower at the time the listing was created.(category)

LoanOriginationDate: The date the loan was originated.

LoanOriginalAmount: The origination amount of the loan.

Recommendations: Number of recommendations the borrower had at the time the listing was created.(category)



## Summary of Findings

### Univariate 
1.The Original amount of loan have very large spikes in frequency at the bars with 5000, (e.g.5000,10000,15000); frequency quickly trails off until the next spike. These probably represent standard loan amount for use specify listing category.
2.The distribution of Borrower rate seems to be normal distribution except the outlier around 0.32.
3.The distribution of the estimated return seems to be a normal distribution that the highist and lowest estimated return are the least common,and the average around 0.1 being the most common.
4.Loan origination date has a long-tailed distribution,with a lots of loans on the 2014,and few on the 2010. When plotted on a log-scale,the nummber of loans seems to be exponential grow from year to year.
5.The most common loan term is 36 month, and next is 60 month, the count of the term of 12 month is the least.
6.Most of the loans in the dataset are actually Current loans. Following it with a big frequency the Completed loans, followed by Chargedoff, while Defaulted,FinalPaymentInProgress and Past due categories loans represent a minority.
7.The distribution of Prosper score seems to be normal distribution.Since it is a custom risk score, so the highest risk and lowest risk is the least common, the median risk is the most common.
8.The vast majority of loans are used for debt consolidation. Other notable categories include Other, Home Improvement and Business.
9.The vast majority of loans are borrowered in California,Other notable regions include Florida,NewYork and Texas.
10.The most borrower's status is employeed and the next is full-time.About the income range, its a roughly normal distribution.But the higher income range obviously have more counts of loans than the lower income range.
11.Most loans are belong to the borrowers which have no recommendations at the time the listing was created, and just a few have one recommendation.
12.Loan Original Amount seems have the negative relationship with the borrower rate.But the increase of loan original amout and borrower rate across increasing term.And loan original amount is increse with the prosper score but Borrower rate is decrease with the prosper score increse. And the loan original amount increse with the increse of the income range,but the borrower rate is decrease with the increase of the income range. which clarify the contradiction.


## Key Insights for Presentation

> With the higher prosperscore, the higher the amount of orginal loan amount.And we can see as the time of term getting longer, the amount of original loan also increased.And generally the income range increased, the loan original amount is also increased.
>Interestingly, the income range from 0 to $1-24999, the loan original amount is decreased.It is clearly that with the increse of the income range(for that income range is not zero) , the loan orignal amount is increased, the loans of longer term also incresed.