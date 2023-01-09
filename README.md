![header](./images/header2.jpg)

## SyriaTel Customer Churn Analysis
**Predicting Customer Churn using Classification Machine Learning**

**Author**: [Nate Kist](mailto:natekist@outlook.com)

## Overview

I analyzed a database of customer data from SyriaTel to determine which customers were churning the most and to predict if a customer was likely to churn soon.  Correct prediction of this type of binary classification can be used by SyriaTel as an early warning system indicating customers at risk of leaving.  From there, SyriaTel can then make business decisions of what to offer its at risk customers in the form of incentives to stay.  

It was found that customers from Maryland, New Jersey, and Texas were churning the most.  Similarly, customers with international plans and customers with 5 or more customer service calls were churning at higher rates.  It was recommended that SyriaTel look into the real-world drivers of these identified issues.  

In the end, I created a classification model that correctly predicted churn with 96% accuracy.  It was recommended that SyriaTel implement this model in its active marketing strategy to prevent loss of customers.  

## Business Understanding

SyriaTel, a US-based telecommunications company, asked me (Nate Kist, of CRM Consulting) to perform an analysis on its customer data to:
1. Provide insight on groups of customers that are churning at higher rates, and
2. Create a model that can predict whether a customer will churn.

## Data Understanding

- No nulls.  No need to impute anything.  
- 3333 rows.  21 columns.  
- Ignore phone number. y will be churn series. Everything else will be in X.  

## Data Preparation
- Figure out feature types for the purpose of column transformers
- Train, test, split the data,
- Create column transformers

## Exploratory Data Analysis 

### Churn by State
![header](./images/1.png)

### Churn by International Plan
![header](./images/2.png)

### Churn by Number of Service Calls
![header](./images/3.png)


## Modeling
### Baseline Model

### Round 1 - Simple Models (default hyperparameters)























