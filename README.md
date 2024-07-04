# CREDIT CARD FRAUD DETECTION

## Introduction 
Credit card fraud is a type of financial fraud. It involves the unauthorised use of someone's credit card information to make fraudulent transactions, leading to financial losses for the cardholder. It is a form of identity theft because it often requires stolen personal information to perpetrate the fraud.

## Overview
Credit card fraud is a critical issue impacting both consumers and businesses worldwide. This research project focuses on exploring various methods and techniques for detecting and preventing fraudulent transactions. The goal is to identify effective strategies to mitigate the risks associated with credit card fraud, ensuring enhanced security and trust in financial transactions.

|Sr.no|Features name| 
 |-|-|
 |1)|Time|
|2)|V1|
|3)|V2|
|4)|V3|
|5)|V4| 
|6)|V5| 
|7)|V6|
|8)|V7|
|9)|V8|
|10)|V9|
|11)|V10|
|12)|V11|
|13)|V12|
|14)|V13|
|15)|V14|
|16)|V15|
|17)|V16|
|18)|V17|
|19)|V18|
|20)|V19|
|21)|V20|
|22)|V21|
|23)|V22|
|24)|V23|
|25)|V24|
|26)|V25|
|27)|V26|
|28)|V27|
|29)|V28|
|30)|Amount|
|31)|Class|

Dataset contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, they cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'

## Steps performed
 1. Import Libraries : 
    Load the necessary Python libraries for data analysis
 2. Import Data :
    Import the dataset containing the features and target variable   
 3. Data Clean :
    Check Null values, Duplicated values
 4. Data Understanding :
    Perform exploratory data analysis to understand the distributions   
 5. Data Visualizations :
    Visualize the data    
 6. Feature Selection :
    See the most relevant features for the modeling process
 7. Machine Learning :
    Develop and evaluate machine learning models
    1) Linear Regression
    2) Decision Tree
8. Testing :
    Best model selected is Decision Tree Regressor (Reason - Recall % is higher ) 
