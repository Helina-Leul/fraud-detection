# Fraud Detection for E-commerce and Banking Transactions

## Project Overview

## Business Problem

## Datasets

### Fraud_Data.csv
### IpAddress_to_Country.csv
### creditcard.csv

## Project Structure

## Task 1: Data Analysis and Preprocessing

### Data Cleaning
### EDA
### Feature Engineering
### Geolocation Integration
### Class Imbalance Handling

## Task 2: Model Building

### Logistic Regression Results

F1 Score: 0.419
AUC-PR: 0.604

### Random Forest Results

F1 Score: 0.693
AUC-PR: 0.651

### Cross Validation

Mean F1: 0.834
Standard Deviation: 0.0058

## Best Model Selection

Random Forest was selected because it achieved the highest F1 Score and AUC-PR while maintaining strong fraud detection capability.

## Task 3: Model Explainability

### Feature Importance
### SHAP Summary Plot
### Force Plot Analysis

## Business Recommendations

1. Verify transactions shortly after signup.
2. Monitor devices with high transaction volume.
3. Apply geographic risk scoring.
4. Use behavioral monitoring.
5. Deploy real-time fraud detection.

## Installation

pip install -r requirements.txt
