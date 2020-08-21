# Bank Loan Status 

Flatiron Module 3 Project
Contributors: Binyamin Zaetz and Lauren Cunningham 

Dataset: Bank Loan Status dataset from Kaggle
https://www.kaggle.com/zaurbegiev/my-dataset


## Overview 

The objective of this project was to create a classification model from a dataset of our choosing and identify a problem we can solve. We used the Bank Loan Status dataset to see whether we could predict if a borrower will default on their loan. This dataset gives us an opportunity to provide lenders with findings and recommendations on how to allocate their capital. Bank profitability and solvency are vital components to both economic and social stability. 


## Process 

1. Data Cleaning
2. EDA
3. Hypothesis Testing
4. Modeling


## Libraries

- Pandas
- Numpy 
- Matplotlib
- Seaborn
- Scipy
- Sklearn


## Modeling

- Baseline
- Bagged Logistic Regression 
- Random Forest 

## Findings & Recommendations 

![Image](/visualizations/income.png)

- Lower income individuals are more likely to default on their loans but it is necessary for banks to be mindful of the economic and opportunity inequality that comes out of this finding. 


![Image](/visualizations/credit_score.png)

- There is a significant difference in loan status between low and high credit score categories. Credit score is a good predictive indicator of whether or not a borrower will default on their loan. 


![Image](/visualizations/credit_probs.png)

- We did not find a significant difference between the number of credit problems and the likeliness of default. However, there are several limitations to this feature. We do not know what is considered a credit problem and different borrowers have different timelines of credit history. If someone were to have had credit problems 10 years ago, that might not affect their likeliness of default today. 


![Image](/visualizations/purpose.png)

- Small businesses default on their loans at the highest rate. This poses yet another challenging question that banks still grapple with today. There must be a balance between their profitability objectives as well as the need to provide small businesses (or lower income individuals) with equal economic opportunity. 


