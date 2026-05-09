# Loan Default Prediction

## Project Overview

This project predicts the likelihood of loan default using machine learning models trained on Lending Club loan data. The objective was to analyze borrower and financial information to identify patterns associated with loan default risk.

The project includes:

* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Feature engineering
* Missing value handling
* Model training and evaluation
* Threshold tuning and performance analysis

## Dataset

The dataset used in this project contains loan application and borrower information from Lending Club.

Some of the variables analyzed include:

* FICO scores
* Debt-to-income ratio (DTI)
* Revolving utilization
* Delinquency history
* Loan amount
* Employment and financial information

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Exploratory Data Analysis

The project includes:

* Correlation matrix analysis
* Missing value analysis
* Pairplots and visualizations
* Feature relationship exploration

## Data Preprocessing

Several preprocessing techniques were applied:

* Missing value imputation
* Feature engineering
* Dimension reduction
* Encoding and variable preparation

Example:

* Combined `fico_range_low` and `fico_range_high` into a new variable called `fico_avg`
* Created delinquency indicators for missing delinquency history

## Machine Learning Models

Models explored in this project include:

* Logistic Regression
* Decision Tree
* Random Forest

## Model Evaluation

The models were evaluated using:

* Accuracy
* ROC AUC
* Confusion Matrix
* Threshold tuning

The project also explores the challenges of imbalanced classification problems in loan default prediction.

## Key Learnings

Through this project I improved my understanding of:

* Predictive modeling
* Classification problems
* Feature engineering
* Model evaluation metrics
* Handling missing data
* Machine learning workflows

## Future Improvements

Potential future improvements include:

* Hyperparameter tuning
* Cross-validation optimization
* Additional feature engineering
* Deployment as a web application
* Model explainability techniques

## Author

Darren Levreault
