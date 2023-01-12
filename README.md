# A Multiple Linear Regression Model for Predicting Insurance Expenses
![insurance](https://user-images.githubusercontent.com/94622826/212007150-ae098f26-5399-4f86-b4c7-7632c800ee2b.png)

## Overview

This project aims to predict insurance premiums for policyholders using a multiple linear regression model. The dataset used for this project was obtained from Kaggle and contains information on policyholder characteristics such as age, BMI, sex, number of children, smoker status, and region.

The project is divided into the following sections:

Business understanding  
Research question  
Objectives  
Data understanding  
Data preparation  
Exploratory data analysis  
Modeling  
Evaluation  
Deployment  
Conclusion  


## Business Understanding

Insurance companies need to understand the factors that influence insurance premiums in order to set premiums that are fair and appropriate for their customers. By analyzing a dataset containing information on policyholder characteristics, insurance companies can gain insights into the relationships between these characteristics and premiums, and use this information to set premiums aligned with the level of risk.
## Research Question

The main objective of this project is to build a model that will predict the insurance premiums that can be used by insurance companies to manage risk and ensure financial stability
## Objectives

To identify the most significant features in determining insurance premiums  

To build a linear regression model that can accurately predict insurance premiums based on input features from the Kaggle insurance premium prediction dataset.  

To assess the performance of the predictive model and identify potential areas for improvement.
## Data Understanding

### Data Source

The dataset used for this project was obtained from Kaggle.  

### Data Description

The insurance.csv dataset contains 7 columns and 1338 observations (rows). The 7 columns contain 4 numerical features (age, bmi, children and expenses) and 3 categorical features (region, sex and smoker).  

### Data Preparation  

The data was cleaned and pre-processed to ensure that it was in a usable form. This was done by removing duplicates and checking for outliers. The data was also validated against an external data source to ensure that it was in line with what it should be.


## Exploratory Data Analysis

The data sets were analyzed and trends found by using statistics and visualizations to aid in comprehending the data set. The questions answered and variable relationships established include:  

At what age is smoking prevalent? (Age vs smoker)  
What regions contribute the highest insurance premiums? (Region vs expense)  
Is there a relationship between BMI and expense? (BMI vs expense)  

## Modeling

Multiple linear regression was used to build the predictive model. A step-by-step process was used to implement the solution which includes:  

Train-test split   
Model fit and summary  
Model diagnostics  
Linear equation  
Mean Absolute Error (MAE)  
Mean Absolute Percentage Error (MAPE)  

## Evaluation

The performance of the predictive model was evaluated using several metrics including R-squared, Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE). The model was found to have an R-squared value of 0.765, a MAE of 1.33 and a MAPE of 12.8%.    

## Conclusion

The model developed in this project can accurately predict insurance premiums for policyholders based on their characteristics. Insurance companies can use this model to manage risk and ensure financial stability by setting premiums that are aligned with the level of risk. Potential areas for improvement include further feature engineering and the use of other predictive modeling techniques.  
s.
