# Credit Card Fraud

## What is Credit Card Fraud ?

Credit card fraud is the unauthorized use of a credit or debit card (or card details) to make purchases or withdraw funds. 

## How does credit card fraud happen? 

Credit card fraud happens when a criminal steals someone else’s credit card information and uses it for their own financial gain.Traditionally, credit card fraud occurred when a physical card was stolen from the owner.
With contemporary credit card fraud, it is increasingly likely a fraudster will obtain a victim’s credit card details, but not the physical card.

## Types of Credit Card Fraud

- Lost or Stolen Card Fraud : Someone finds or steals your physical card and uses it to make unauthorized purchases. 

 - Card-not-Present (CNP) Fraud : When someone uses stolen card details online, over the phone, or via mail without having the physical card. 

 - Counterfeit Card Fraud : Criminals create a fake copy of a card using stolen data from skimming devices. 

 - Application Fraud : Someone applies for a credit card using stolen personal information (identity theft). 

 - Account Takeover Fraud : A fraudster gains access to a victim's account, changes login details, and makes transactions. 

 - Phishing and Social Engineering : Fraudsters trick people into revealing card details through fake emails, phone calls, or websites.

# Project : Credit Card Fraud Detection Predictive Models

## Content 

- Load packages
- Read the data
- Check the data
  - Glimpse the data
  - Check missing data
  - Check data unbalance
- Data exploration
- Predictive models
  - RandomForrestClassifier
  - AdaBoostClassifier
  - CatBoostClassifier
  - XGBoost
  - LightGBM

## Introduction

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation.

- Features V1, V2, ... V28 are the principal components obtained with PCA;
- The only features which have not been transformed with PCA are Time and Amount. Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
- Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.
