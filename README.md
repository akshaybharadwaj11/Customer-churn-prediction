# Customer-churn-prediction

This repository contains code for performing Binary Classification on the [Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset) taken from Kaggle. Classification Models used 
- Logistic Regression
- Decision Tree
- H20 AutoML (Gradient Boosting Machine was the best model)

We compare the models and interpret them using Partial Dependence Plots and Shap values to understand the model predictions and influence of different features

### Dataset

This dataset has 10000 records and 12 columns(11 features and a target variable(Churn) containing details of customers for ABC Multistate bank.

* customer_id - unique id representing each customer
* credit_score - credit score for each customer
* country - location of the account
* gender - customer gender
* age - age of customer
* tenure -  duration with the bank for each customer
* balance - account balance
* products_number -  number of bank products utilized by the customer
* credit_card - no of credit cards held by customer
* active_member - 0 or 1, does the customer regularly use the services offered by the bank
* estimated_salary -  salary of customer
* churn - target variable. 1 if the client has left the bank during some period or 0 if he/she has not.

### Packages to be installed

! pip install -q kaggle
! pip install h2o
! pip install shap

**Note** : This Notebook can run on Google Colab. To import the kaggle dataset, download the API key from your kaggle account and name it as "kaggle.json". Upload the kaggle.json while running the "upload.files" cell in the notebook
