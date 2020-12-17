# Telecom-churn-classification:

Overview:

In this project, customer-level data of a leading telecom firm is analyzed, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

Problem Statement:

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.This project is based on the Indian and Southeast Asian market.

In this project, you will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

The below files are uploaded:

1. telecom_churn_data.csv : The dataset can be download using this link : https://drive.google.com/file/d/1SWnADIda31mVFevFcfkGtcgBHTKKI94J/view

2. TelcomChurnCaseStudyDataDescription.xlsx : This file contains data dictionary used to understand the features in the csv file. The data dictionary contains meanings of abbreviations. Some frequent ones are loc (local), IC (incoming), OG (outgoing), T2T (telecom operator to telecom operator), T2O (telecom operator to another operator), RECH (recharge) etc.The attributes containing 6, 7, 8, 9 as suffixes imply that those correspond to the months 6, 7, 8, 9 respectively.

3. TelecomChurnCaseStudy.ipynb: This file contains python code for model building and prediction.

Brief Summary of solution:

The data set conatins 99999 rows and 216 columns.The data is well inspected.The missing value analysis is performed.Replaced meaningful missing values with zero.Also,used advanced imputation KNN technique.EDA is performed and concluded that data was highly skewed. So for treating outliers,log transformation was performed.The data was highly imbalanced.So SMOTE data imbalancing was also performed. Since there are more number of features,derived new features by combining few features and also PCA is used to reduce dimensions. Finally, below 4 models are build:
 - An interpretable model using Logistic Regression without PCA
 - Logistic Regression with PCA
 - Random Forest Classifer with PCA
 - XGBoost Classifier with PCA
And concluded with business recommendations.
 


