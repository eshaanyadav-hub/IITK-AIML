# Feature Engineering for House Price Prediction

## Project Overview

This project was completed as part of the **Applied Data Science with Python** course. The objective is to identify the key factors that influence residential property prices in Ames, Iowa, using feature engineering and exploratory data analysis techniques.

The dataset contains **79 explanatory variables** describing various aspects of residential homes, including physical characteristics, location attributes, construction quality, and other housing features.

## Problem Statement

While searching for a dream house, buyers evaluate numerous factors beyond obvious characteristics such as basement height or proximity to transportation infrastructure. The goal of this project is to determine the variables that significantly influence house prices and prepare a clean dataset suitable for machine learning model development.

## Dataset

* Dataset: `PEP1.csv`
* Location: Ames, Iowa, USA
* Target Variable: House Sale Price
* Features: 79 explanatory variables
* Data Types:

  * Numerical Variables
  * Categorical Variables

## Project Objectives

### 1. Data Understanding

* Examined dataset dimensions and structure
* Identified missing values across variables
* Identified variables with unique values
* Segregated numerical and categorical features

### 2. Exploratory Data Analysis (EDA) – Numerical Variables

* Performed missing value treatment
* Analyzed distributions and skewness
* Generated correlation matrix to identify significant variables
* Created pair plots for distribution and relationship analysis

### 3. Exploratory Data Analysis (EDA) – Categorical Variables

* Treated missing values
* Conducted bivariate analysis using count plots
* Evaluated feature significance using:

  * Chi-Square Tests
  * P-Values

### 4. Feature Selection

* Combined significant numerical and categorical features
* Reduced dimensionality by removing less relevant variables
* Prepared a refined dataset for model training

### 5. Outlier Detection

* Generated box plots for selected features
* Identified potential outliers
* Evaluated data quality prior to model development

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn
* Jupyter Notebook

## Key Analytical Techniques

* Missing Value Imputation
* Correlation Analysis
* Feature Engineering
* Distribution Analysis
* Chi-Square Testing
* Outlier Detection
* Data Visualization

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Treatment
4. Numerical Feature Analysis
5. Categorical Feature Analysis
6. Feature Selection
7. Outlier Detection
8. Dataset Preparation for Machine Learning

## Repository Structure

```text
Feature-Engineering-House-Prices/
│
├── Feature_Engineering.ipynb
├── PEP1.csv
├── README.md
└── data_description.txt
```

## Learning Outcomes

Through this project, the following concepts were applied:

* Exploratory Data Analysis (EDA)
* Statistical Testing
* Feature Engineering
* Data Cleaning
* Data Visualization
* Dataset Preparation for Predictive Modeling

## Author

**Eshaan Yadav**

Applied Data Science with Python – Course End Project

