# A Multiple Linear Regression Model for Predicting Insurance Expenses
![insurance](https://user-images.githubusercontent.com/94622826/212007150-ae098f26-5399-4f86-b4c7-7632c800ee2b.png)

## Overview

This project aims to predict insurance premiums for policyholders using a multiple linear regression model. The dataset used for this project was obtained from kaggle here is the link [kaggle](https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction) and contains information on policyholder characteristics such as age, BMI, sex, number of children, smoker status, and region.

### Dependecies

* python3
* numpy
* pandas
* seaborn
* sklearn
* statsmodels
* matplotlib
* category_encoders
* scipy

The project is divided into the following sections:

* Business understanding  
* Research question  
* Objectives  
* Data understanding  
* Data preparation  
* Exploratory data analysis  
* Modeling  
* Evaluation    
* Conclusion  


## Business Understanding

Insurance companies need to understand the factors that influence insurance premiums in order to set premiums that are fair and appropriate for their customers. By analyzing a dataset containing information on policyholder characteristics, insurance companies can gain insights into the relationships between these characteristics and premiums, and use this information to set premiums aligned with the level of risk.

## Research Question

The main objective of this project is to build a model that will predict the insurance premiums that can be used by insurance companies to manage risk and ensure financial stability
## Objectives

* To identify the most significant features in determining insurance premiums  

* To build a linear regression model that can accurately predict insurance premiums based on input features from the Kaggle insurance premium prediction dataset.  

* To assess the performance of the predictive model and identify potential areas for improvement.
## Data Understanding

### Data Source

The dataset used for this project was obtained from Kaggle.  

### Data Description

The insurance.csv dataset contains 7 columns and 1338 observations (rows). The 7 columns contain 4 numerical features (age, bmi, children and expenses) and 3 categorical features (region, sex and smoker).  

### Data Preparation  

The data was cleaned and pre-processed to ensure that it was in a usable form. This was done by removing duplicates and checking for outliers. The data was also validated against an external data source to ensure that it was in line with what it should be. Using exploratory data analysis, the data sets were analyzed and trends found by using statistics and visualizations to aid in comprehending the data set. 
## Modeling

Multiple linear regression was used to build the predictive model. In summary, the data modeling process for insurance premium prediction using Linear regression involved checking the correlation between the predictor and target variables, which resulted in weak correlations for all predictor variables. Binary encoding was used to convert the categorical data into a form that can be used by the Ordinary Least Squares (OLS) model. The Least Squares Method (LSM) was used to fit the model and it was found to be statistically significant with a probability of F-statistic below 0.05. The model was able to explain 74.8% of the variation in the insurance premium and had a Mean Absolute Percentage Error (MAPE) of 42.26%. However, it was also found that there existed a non-linear relationship between the predictors and the response variable and there was some evidence of heteroskedasticity as the residuals displayed a funnel-shape  
A second model was fitted to to deal with the non-linear relationships between the predictor and response. The target, age and BMI was log transformed and fitted using OLS where the model's Adjusted R-squared increase to 76 %. The MAPE also reduced significantly to 23 %.
The final model was fitted to further refine the non-linear relationships. After log-transforming the target and including interaction terms for between smoker, age and BMI, the final model improved further to record an R-squared of 82%. It also recorded a MAPE of 10 %

## Evaluation

The performance of the predictive model was evaluated using several metrics including R-squared and Mean Absolute Percentage Error (MAPE). The final model was found to have an R-squared value of 0.821, a MAPE of 10%.    

## Conclusion

The model developed in this project can accurately predict insurance premiums for policyholders based on their characteristics. Insurance companies can use this model to manage risk and ensure financial stability by setting premiums that are aligned with the level of risk. Potential areas for improvement include further feature engineering and the use of other predictive modeling techniques.  
