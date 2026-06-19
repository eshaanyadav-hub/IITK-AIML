# Lending Club Loan Default Prediction using Deep Learning

## Project Overview

This project was completed as part of the **Deep Learning with Keras and TensorFlow Course-End Project**. The objective is to build a deep learning model that predicts whether a loan issued by Lending Club is likely to default based on historical lending data from 2007–2015.

The project combines exploratory data analysis, feature engineering, dimensionality reduction, and neural network modeling to solve a real-world financial risk assessment problem. :contentReference[oaicite:0]{index=0}

---

## Problem Statement

For lending institutions, accurately predicting loan defaults is critical for minimizing financial losses and improving credit decision-making.

Using historical Lending Club loan data, this project aims to develop a predictive deep learning model that estimates the probability of a loan default. The dataset is highly imbalanced and contains numerous borrower and loan-related features, making the prediction task more challenging. :contentReference[oaicite:1]{index=1}

---

## Business Objective

- Predict loan default risk
- Improve lending decisions
- Reduce credit losses
- Identify high-risk borrowers
- Support risk-based pricing and underwriting

---

## Dataset Description

The dataset contains historical Lending Club loan records and borrower information.

### Key Features

- Credit Policy Eligibility
- Loan Purpose
- Interest Rate
- Monthly Installment
- Annual Income
- Debt-to-Income Ratio
- FICO Credit Score
- Credit Line History
- Revolving Balance
- Credit Utilization Rate
- Credit Inquiries
- Delinquencies
- Public Records

The target variable indicates whether a loan defaulted or was successfully repaid. :contentReference[oaicite:2]{index=2}

---

## Project Workflow

### 1. Data Exploration

- Loaded and inspected the dataset
- Reviewed feature distributions
- Analyzed borrower characteristics
- Identified patterns in loan defaults

### 2. Data Preprocessing

- Checked for missing values
- Cleaned inconsistent records
- Prepared data for modeling
- Standardized numerical features

### 3. Feature Transformation

Categorical variables were transformed into numerical representations suitable for machine learning models.

Examples include:

- Loan Purpose Encoding
- Credit Policy Encoding
- Other categorical feature transformations

### 4. Exploratory Data Analysis (EDA)

Performed detailed analysis of:

- Credit Scores
- Interest Rates
- Income Levels
- Debt-to-Income Ratios
- Revolving Credit Utilization
- Loan Purposes

Visualizations were used to identify trends and factors associated with loan defaults.

### 5. Feature Engineering

To improve model performance:

- Correlation analysis was performed
- Highly correlated features were identified
- Redundant variables were removed
- Most relevant predictors were retained

This reduced dimensionality and improved model efficiency. :contentReference[oaicite:3]{index=3}

---

## Deep Learning Model Development

A neural network was developed using:

- TensorFlow
- Keras

### Model Architecture

- Input Layer
- Multiple Hidden Dense Layers
- Activation Functions
- Dropout Layers
- Binary Classification Output Layer

The model was trained to classify loans as:

- Default
- Non-Default

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

### Performance Analysis

Special attention was given to:

- False Negatives (missed defaults)
- Class Imbalance Challenges
- Generalization Performance

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Deep Learning Concepts Applied

- Binary Classification
- Neural Networks
- Feature Engineering
- Feature Selection
- Correlation Analysis
- Data Preprocessing
- Model Evaluation
- Financial Risk Analytics

---

## Repository Structure

```text
07-Peer-to-Peer-Lending-Risk-Analysis/
│
├── README.md
├── lending_club_default_prediction.ipynb
├── lending_club_dataset.csv
├── saved_models/
└── results/
