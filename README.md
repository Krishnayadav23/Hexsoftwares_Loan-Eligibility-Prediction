# Hexsoftwares_Loan-Eligibility-Prediction
The Loan Eligibility Prediction project is a machine learning solution that predicts whether a loan application will be approved or not. This project uses real-world data to analyze key factors influencing loan eligibility and implements a predictive model using Random Forest Classifier.
# Loan Eligibility Prediction  

This repository contains a machine learning project designed to predict loan eligibility based on applicant details. The project leverages a Random Forest Classifier for robust and accurate predictions.  

## Table of Contents  
1. [Introduction](#introduction)  
2. [Dataset](#dataset)  
3. [Requirements](#requirements)  
4. [Installation](#installation)  
5. [Features](#features)  
6. [Usage](#usage)  
7. [Results](#results)  
8. [License](#license)  

---

## Introduction  
Loan eligibility is a crucial factor in the lending process. This project aims to automate the eligibility assessment process by building a predictive machine learning model.

## Dataset  
The dataset includes applicant demographic, financial, and loan-related information. Key features include:  
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Credit History  
- Property Area  

The target variable is **Loan_Status**, which indicates whether the loan is approved (`1`) or not (`0`).  

## Requirements  
The project requires the following Python libraries:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/loan-eligibility-prediction.git
#Features
Data preprocessing (cleaning, encoding, and handling missing values).
Feature engineering to extract meaningful insights.
Implementation of Random Forest Classifier.
Detailed performance evaluation and feature importance analysis.
#Usage
Load the dataset and preprocess it.
Train the Random Forest model using the provided scripts.
Evaluate the model's performance using the test dataset.
#Results:
Achieved an accuracy of 78% on the test data.
Feature importance analysis reveals that Credit History and Applicant Income are key predictors of loan eligibility.
License
