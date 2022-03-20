# Supervised Machine Learning Homework - Predicting Credit Risk

In this project I built a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

I used this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.


## Preprocessing: Convert categorical data to numeric

Creatd a training set from the 2019 loans using `pd.get_dummies()` to convert the categorical data to numeric columns. Similarly, created a testing set from the 2020 loans, also using `pd.get_dummies()`. 

## Consider the models

Created and compared two models on this data: a logistic regression, and a random forests classifier. 

## Fit a LogisticRegression model and RandomForestClassifier model

Created a LogisticRegression model, fit it to the data, and prined the model's score. Same was done for a RandomForestClassifier. 

## Revisit the Preprocessing: Scale the data

 Used `StandardScaler` to scale the training and testing sets. 

Fit and scored the LogisticRegression and RandomForestClassifier models on the scaled data. 