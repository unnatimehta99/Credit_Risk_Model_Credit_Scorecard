# Credit Risk Model and Credit Scoring

## Introduction
This project focuses on developing a data-driven credit risk model in Python, utilizing an interpretable scorecard to predict default probabilities and assign credit scores to borrowers. The aim is to enhance understanding and predictive capabilities in a step-by-step manner, making the credit score calculation process accessible and effective.

## Problem Definition
The challenge involves creating a reliable credit risk model, addressing issues such as missing values, irrelevant features, and selecting appropriate loan_status values indicative of default. The project aims to streamline data cleaning, feature selection, and model implementation for robust credit risk assessment.

## Data Overview
Dataset: https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014
The dataset, named Credit_Modeling_Scoring, sourced from Kaggle, comprises information on over 450,000 consumer loans issued by the Lending Club between 2007 and 2014. The dataset presents challenges, including features with high missing values, irrelevant columns, and forward-looking variables. The goal is to preprocess the data, classify default and good loans, and split it into training and test sets for model evaluation.

## Model Implementation
he meticulous steps in data preprocessing and feature selection contribute to a robust framework for model implementation and evaluation.

The implementation phase includes critical steps such as:
* One-hot encoding, WoE binning for numerical and categorical variables.IV assists in ranking features based on their relative importance and is used in tandem with Weight of Evidence (WoE) analysis.
* Logistic regression with cost-sensitive learning. The model is trained on the training set.
* Performance is evaluated using metrics like ROC curve, PR curve, AUROC, and Gini to ensure its effectiveness in predicting credit risk. T

## Model Evaluation:
The logistic regression model is evaluated using RepeatedStratifiedKFold testing. ROC and PR curves visualize the model's performance, confirming its acceptability in predicting credit risk. These metrics serve as a comprehensive assessment of the model's accuracy and reliability.

## Conclusion:
In conclusion, the project successfully develops a Python-based credit risk model, providing an interpretable scorecard for predicting default probabilities and assigning credit scores. The meticulous steps taken in data preprocessing, feature selection, and model evaluation contribute to a robust framework for effective credit risk assessment in the financial domain.
