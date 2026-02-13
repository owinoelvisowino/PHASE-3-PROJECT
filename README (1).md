
# Predicting Customer Churn for SyriaTel

## Overview
This project builds a classification model to predict whether a customer will churn. 
The goal is to help SyriaTel reduce revenue loss through proactive retention strategies.

## Business and Data Understanding
Stakeholder: SyriaTel Customer Retention Team

Business Problem:
Customer churn reduces recurring revenue. Identifying customers likely to leave enables targeted retention campaigns.

Dataset:
Contains customer usage data, account details, service subscriptions, and churn status (binary target).

## Modeling
Baseline Model: Logistic Regression  
Improved Model: Random Forest with tuned hyperparameters  

Class imbalance addressed using class_weight='balanced'.

## Evaluation
Primary Metric: Recall  

Recall was prioritized because missing a churner results in direct revenue loss.

Final Model: Random Forest selected based on superior recall and overall performance.

## Conclusion
The model successfully identifies high-risk customers, enabling SyriaTel to implement targeted retention strategies and reduce churn-related losses.
