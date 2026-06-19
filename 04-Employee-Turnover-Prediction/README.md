# Employee Turnover Prediction and Analytics

## Project Overview

This project was completed as part of the **Machine Learning Course-End Project**. The objective is to analyze employee data, identify factors contributing to employee turnover, and develop predictive machine learning models that help organizations proactively manage employee retention.

The project combines exploratory data analysis, clustering, class imbalance handling, machine learning classification models, and business-oriented retention strategies.

---

## Problem Statement

Portobello Tech aims to predict employee turnover using historical employee performance and workplace data. Employee turnover refers to employees leaving the organization and can significantly impact productivity, recruitment costs, and organizational performance.

The goal of this project is to:

* Understand key drivers of employee attrition
* Identify patterns among employees who leave
* Build predictive models for turnover prediction
* Handle class imbalance using SMOTE
* Compare multiple machine learning algorithms
* Recommend retention strategies based on employee risk levels

---

## Dataset Description

The dataset contains employee information including:

### Features

* Satisfaction Level
* Last Evaluation Score
* Number of Projects
* Average Monthly Working Hours
* Time Spent in Company
* Work Accident History
* Promotion in Last 5 Years
* Department
* Salary Level

### Target Variable

* **left**

  * 0 = Employee Stayed
  * 1 = Employee Left

---

## Project Workflow

### 1. Data Quality Assessment

* Checked for missing values
* Examined data consistency
* Identified potential anomalies
* Prepared data for analysis

### 2. Exploratory Data Analysis (EDA)

Performed extensive analysis to identify factors influencing employee turnover.

#### Visualizations

* Correlation Heatmap
* Employee Satisfaction Distribution
* Employee Evaluation Distribution
* Monthly Working Hours Distribution
* Project Count Analysis
* Attrition-Based Comparisons

#### Key Objectives

* Understand turnover patterns
* Identify influential features
* Explore employee behavior trends

---

### 3. Employee Clustering

Applied clustering techniques to employees who left the company.

#### Methodology

* Selected:

  * Satisfaction Level
  * Last Evaluation Score
* Applied K-Means Clustering
* Segmented employees into 3 distinct clusters

#### Outcome

Identified groups of employees with different attrition characteristics and workplace behaviors.

---

### 4. Class Imbalance Handling

Employee turnover datasets typically contain class imbalance.

#### Preprocessing

* Separated categorical and numerical features
* Applied One-Hot Encoding using `get_dummies()`
* Combined transformed datasets

#### SMOTE

Applied Synthetic Minority Oversampling Technique (SMOTE) to balance the training data and improve model performance.

---

### 5. Machine Learning Models

Implemented and evaluated multiple classification algorithms.

#### Models Trained

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

#### Validation Strategy

* 5-Fold Cross Validation
* Stratified Train-Test Split (80:20)
* Random State = 123

---

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

#### Comparative Analysis

* ROC Curves
* Classification Reports
* Model Performance Comparison

The best-performing model was selected based on predictive accuracy and business relevance.

---

### 7. Employee Risk Segmentation

Predicted employee turnover probabilities and categorized employees into risk groups.

| Zone   | Probability Range | Risk Level  |
| ------ | ----------------- | ----------- |
| Green  | < 20%             | Safe Zone   |
| Yellow | 20% – 60%         | Low Risk    |
| Orange | 60% – 90%         | Medium Risk |
| Red    | > 90%             | High Risk   |

---

### Retention Strategy Framework

#### Safe Zone (Green)

* Maintain engagement
* Continue development opportunities

#### Low Risk Zone (Yellow)

* Conduct periodic feedback sessions
* Monitor workload and satisfaction

#### Medium Risk Zone (Orange)

* Career progression discussions
* Compensation benchmarking
* Targeted employee engagement programs

#### High Risk Zone (Red)

* Immediate HR intervention
* Managerial review
* Personalized retention plans
* Role redesign or promotion consideration

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Jupyter Notebook

---

## Machine Learning Concepts Applied

* Exploratory Data Analysis
* Feature Engineering
* Data Preprocessing
* One-Hot Encoding
* K-Means Clustering
* Class Imbalance Handling
* SMOTE
* Logistic Regression
* Random Forest
* Gradient Boosting
* Cross Validation
* ROC-AUC Analysis

---

## Repository Structure

```text
04-Employee-Turnover-Prediction/
│
├── README.md
├── employee_turnover_prediction.ipynb
├── employee_data.csv
└── supporting_files/
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Employee Analytics
* Predictive HR Analytics
* Unsupervised Learning
* Supervised Learning
* Class Imbalance Management
* Model Evaluation and Selection
* Business-Oriented Machine Learning Solutions

---

## Author

**Eshaan Yadav**

Machine Learning Course-End Project – IIT Kanpur AIML Program

