# Customer_Churn_prediction# Customer Churn Prediction Using Machine Learning

## Overview

This project predicts customer churn using machine learning on a highly imbalanced dataset. The objective was to evaluate the impact of SMOTE and Stratified K-Fold Cross Validation while preventing data leakage.

## Dataset

* 200 customer records
* 5 numerical features
* Binary churn target
* Class distribution: 190 non-churners and 10 churners

## Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest

## Techniques Used

* Exploratory Data Analysis (EDA)
* StandardScaler
* SMOTE (Synthetic Minority Oversampling Technique)
* Stratified K-Fold Cross Validation (K=10)
* Hyperparameter Tuning

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

## Key Result

Logistic Regression with SMOTE achieved the best performance, improving recall from 30% to 80%.

## Installation

```bash
pip install -r requirements.txt
```

## Repository Contents

* Prediction.ipynb
* Report.pdf
* requirements.txt
