
# Predictive Model to Catch Fradulent Bank Transactions
This Project is made for PredCatch Analytics. They are being hit by Fraudent ATM transactions which affect thir Reputation and Profitability. This Model helps in reducing and possibly completely eliminating such Fradulent transactions by catching them in real time and declining them.

## About the Dataset
The Dataset contains data of very few fradulent Transactions in comparison to he overall population. The data which got collected regarding : 
* Locations of the Transaction [geo_scores] 
* Proprietary Index [Lambda_wts] 
* On Network Turn around times [Qset_tats]
* Vulnerability Qualification score [instance_scores]

For Training and Testing Purposes data has been divided into seperate csv files. Since, it is a real time data so the column names has been modified and renamed.

The Target variable is either 0 or 1 

1: Fraudulent transactions
0: Clean transaction

## Installation and Dependencies

These are the required packages and Dependencies

* os
* numpy
* pandas
* matplotlib
* seaborn
* warnings
* scikit-learn
* xgboost