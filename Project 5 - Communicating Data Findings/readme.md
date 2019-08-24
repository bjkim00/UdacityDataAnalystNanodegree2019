# Exploring Loan Data from Prosper
## by Byungjin (BJ) Kim


## Dataset

The dataset gave access to many different aspects of loans. These included things like loan term length, montly loan payment amount, number of investors, loan listing key, etc. One problem that arose when trying to clean the data was that when I simply tried to get rid of any rows that had any null values, then in total, all of the rows in the dataset got removed. Thus, I comprised with this problem and made sure to base all my explorations of the dataset with rows/variables that didn't have any missing values. Regarding duplicated values, there were no duplicated rows within the dataset, so I did not have to worry about that when cleaning the data.


## Summary of Findings

The number of loans per term length, we can see that a loan term length of 36 months was the most popular among this dataset.

The number of investors based on whether or not the borrower is a homeowner, we found that the average number of investors, the higher bound/upper quartile, and the lower bound/lower quartile is higher when the borrower was a homeowner. We could also infer that due to the higher outliers when the borrowers were homeowners, that could have brought up the average, upper quartile, and lower quartile.

We found by analyzing the regression lines, it seems like there are typically the highest ratio of investors per monthly loan payment when the income range is $75,000-99,000.

