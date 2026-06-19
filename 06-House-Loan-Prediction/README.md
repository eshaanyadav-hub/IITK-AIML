# House Loan Default Prediction using Deep Learning

## Project Overview

This project was completed as part of the **Deep Learning with Keras and TensorFlow Course-End Project**. The objective was to develop a deep learning model capable of predicting whether a loan applicant is likely to default on a loan using historical lending data.

The project focuses on handling highly imbalanced financial data, performing data preprocessing, feature encoding, and building a neural network model to support data-driven lending decisions. :contentReference[oaicite:0]{index=0}

---

## Problem Statement

For a safe and secure lending experience, financial institutions must assess the risk associated with loan applicants before approving credit. This project aims to predict the probability of loan default using historical customer data and deep learning techniques.

The dataset presents an additional challenge due to class imbalance and the large number of available features. :contentReference[oaicite:1]{index=1}

---

## Business Objective

- Predict whether an applicant will repay a loan
- Identify high-risk borrowers
- Reduce default-related losses
- Improve credit risk assessment
- Support data-driven lending decisions

---

## Dataset Description

The dataset contains historical loan application and repayment records.

### Target Variable

- **TARGET**
  - 0 = Loan Repaid
  - 1 = Loan Default

The dataset is highly imbalanced, requiring special preprocessing and balancing techniques prior to model training. :contentReference[oaicite:2]{index=2}

---

## Project Workflow

### 1. Data Exploration

- Loaded the dataset
- Examined feature distributions
- Identified missing values
- Assessed data quality

### 2. Data Preprocessing

- Handled null values
- Cleaned and transformed features
- Prepared data for modeling
- Encoded categorical variables

### 3. Class Imbalance Analysis

- Calculated default-to-repayment ratio
- Visualized class distribution
- Applied balancing techniques where necessary

### 4. Feature Engineering

- Encoded categorical variables
- Scaled numerical features
- Created model-ready datasets

### 5. Deep Learning Model Development

Built a neural network using TensorFlow and Keras.

#### Model Components

- Input Layer
- Hidden Dense Layers
- Activation Functions
- Dropout Layers
- Output Layer for Binary Classification

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- Sensitivity (Recall)
- ROC-AUC Score
- Confusion Matrix
- Classification Metrics

### Key Metrics

#### Sensitivity

Measures the model's ability to correctly identify loan defaulters.

#### ROC-AUC

Evaluates the model's ability to distinguish between defaulters and non-defaulters across different classification thresholds.

---

## Visualizations

- Missing Value Analysis
- Class Distribution Plots
- Balanced vs Imbalanced Dataset Comparison
- ROC Curve
- Confusion Matrix
- Model Performance Curves

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
- Feature Encoding
- Data Preprocessing
- Class Imbalance Handling
- Sensitivity Analysis
- ROC-AUC Evaluation
- Financial Risk Modeling

---

## Repository Structure

```text
06-House-Loan-Prediction/
│
├── README.md
├── house_loan_prediction.ipynb
├── loan_dataset.csv
├── saved_model/
└── results/
