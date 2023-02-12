# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to use machine learning to predict credit risk. The dataset is provided by LendingClub and we will utilize imbalance-learn and scikit-learn libraries in Jupyter Notebook. For training, we'll use RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN algorithms. We'll also be using BalancedRandomForestClassifier and EasyEnsembleClassifier to compare our analysis.

## Results

### RandomOverSampler
- accuracy score: 0.6466
- precision score: 0.99
### SMOTE
- accuracy score: 0.6624
- precision score:  0.99
### ClusterCentroids
- accuracy score: 0.5442
- precision score: 0.99  
### SMOTEENN
- accuracy score: 0.6400
- precision score:  0.99
### BalancedRandomForestClassifier
- accuracy score: 0.7885
- precision score: 0.99
### EasyEnsembleClassifier 
- accuracy score: 0.9317
- precision score: 0.99

## Summary

Per our analysis, we have determined the best algorithm to predict credit is would be the EasyEnsembleClassifier which as an accuracy score of 0.9317 and a precision socre of 0.99. 
