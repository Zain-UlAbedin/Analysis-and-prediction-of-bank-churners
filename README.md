# Analysis of Bank Customers TurnOver
## Overview of the project
* Did a thorough analysis of the dataset that I found very interesting. The data set was aboiut customers leaving their banks.
* I analyzed every attribute of the datasets to see hidden patterns that could lead a customer to decide leaving the bank
* Left no stone unturn, I found many causes that lead the customer to leave the bank.
* Build Logistic Regression, and checked it on imbalanced, undersample and oversampled data.
* As the data was very imbalanced, the model was trained and tested on under and over samples datasets.
* Gave very important Insights and recommendation that bank should apply to get low percentage of Customers turnover.


## Resoruces and Code used
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, imblearn
**Dataset on Kaggle:** https://www.kaggle.com/ulhasbhagwat/bankchurners 

## EDA
Before doing Data preparation I did EDA and the reason is there were 6 attributes with categorical data, and I wanted to analyze them before applying onehotencoding on them to ready the
dataset for model. The EDA Analysis was thorough.


## Data Preparation
Data Cleaning was not needed thought, I needed to tend to the categorical data, I used Labelencoder to transform the categorical data into modle understanding numerical data.

## Insights and Recommendations
Some insights that were extracted during the whole EDA analysis.
* Banks should first focus on giving more and more Gold and Platinum Cards, as these customers are spending almost double the amount the Blue card holder spends.
* It was observed that Banks and Customer have mostly 2 to 3 contacts over the course of years, this could problematic, not hearing from your banks leads many astray. 
  Banks should contact theri customer more frequently and let the marketing team be in touch with them. They should also give discounts/special offers to their loyal customers.
* We also noticed that Singles and Divorced spends more then Married Customers, so the company should focus on improving their strategy to attract more Divorced and Single 
  Customers.
* Banks should focus their manpower on implementing a marketing strategy that is most appealing to Customer's aging 27-32 years as they spends the most 
  (The more the customer spends the better for the bank), and this also will make the banks target audience very compact/less, they should if needed be then focus on 
  getting Customer aging 40-52 because that is the second group that spends more. Banks should avoid Customer that are of age 62+ because they spends as little as they can.
