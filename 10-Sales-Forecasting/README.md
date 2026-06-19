# Sales Forecasting using Machine Learning & Deep Learning

## Overview

This project focuses on forecasting restaurant sales using Machine Learning and Deep Learning techniques. The objective is to help businesses make informed decisions regarding inventory management, staffing, production planning, and revenue optimization by accurately predicting future sales demand. The project analyzes historical sales data across multiple restaurants and menu items, performs exploratory data analysis, and develops forecasting models to estimate future sales performance. 

---

## Business Problem

In a competitive business environment, accurate demand forecasting is essential for operational efficiency and strategic decision-making. Restaurant managers rely on sales forecasts to:

* Optimize inventory procurement
* Reduce food wastage
* Plan staffing requirements
* Improve profitability
* Support long-term business planning

Fresh Analytics, a data analytics company, aims to understand and predict item demand across restaurants by analyzing historical sales patterns and building predictive models. 

---

## Project Objectives

The primary objectives of this project are:

* Analyze historical sales trends across restaurants
* Identify seasonal and temporal sales patterns
* Compare restaurant performance over time
* Discover top-selling and high-revenue items
* Build Machine Learning forecasting models
* Develop an LSTM-based Deep Learning forecasting model
* Generate future sales forecasts for business planning



---

## Dataset Information

The project uses three datasets:

### 1. restaurants.csv

Contains information about restaurant locations.

| Variable | Description                  |
| -------- | ---------------------------- |
| id       | Unique restaurant identifier |
| name     | Restaurant name              |

### 2. items.csv

Contains menu item information.

| Variable | Description            |
| -------- | ---------------------- |
| id       | Unique item identifier |
| store_id | Restaurant identifier  |
| name     | Item name              |
| kcal     | Calorie content        |
| cost     | Unit cost of item      |

### 3. sales.csv

Contains historical transaction records.

| Variable   | Description          |
| ---------- | -------------------- |
| date       | Purchase date        |
| item_id    | Item identifier      |
| item_count | Number of items sold |
| price      | Unit selling price   |



---

## Project Workflow

### Data Preparation

* Import datasets
* Data quality assessment
* Missing value analysis
* Outlier detection
* Dataset merging
* Feature engineering

Final merged dataset includes:

* Date
* Item ID
* Item Name
* Item Count
* Price
* Calories
* Store ID
* Store Name



---

## Exploratory Data Analysis

### Sales Trend Analysis

* Daily sales patterns
* Weekly seasonality
* Monthly trends
* Quarterly sales comparison
* Year-over-year growth analysis

### Restaurant Performance Analysis

* Revenue by restaurant
* Sales volume comparison
* Best-performing stores
* Temporal performance trends

### Product Analysis

* Most popular items overall
* Best-selling item per store
* Highest revenue-generating items
* Most expensive items and calorie comparison

### Revenue Analysis

* Daily revenue patterns
* Store-wise profitability
* Volume versus revenue comparison



---

## Machine Learning Models

Three forecasting models are developed and compared:

### Linear Regression

A baseline statistical model used to establish forecasting benchmarks.

### Random Forest Regressor

An ensemble learning algorithm capable of capturing nonlinear relationships within sales data.

### XGBoost Regressor

A gradient boosting framework optimized for predictive accuracy and performance.

### Feature Engineering

Time-based features include:

* Day of Week
* Day of Month
* Month
* Quarter
* Year
* Seasonal Indicators

### Model Evaluation

Performance is evaluated using:

```text
Root Mean Square Error (RMSE)
```

The last six months of data are reserved as the testing dataset.

The best-performing model is used to forecast sales for the next year. 

---

## Deep Learning Forecasting

### Long Short-Term Memory (LSTM)

A Long Short-Term Memory neural network is implemented to capture temporal dependencies in historical sales data.

#### Process

1. Generate sales amount series
2. Create training and testing sequences
3. Generate synthetic data for the final 12 months
4. Train LSTM architecture
5. Predict future sales values
6. Evaluate forecasting performance

### Evaluation Metric

```text
Mean Absolute Percentage Error (MAPE)
```

A second LSTM model is trained using the entire dataset and used to forecast sales for the next three months. 

---

## Technology Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Plotly

### Machine Learning

* Scikit-learn
* XGBoost

### Deep Learning

* TensorFlow
* Keras

### Development Environment

* Jupyter Notebook
* Google Colab
* VS Code

---

## Expected Deliverables

* Cleaned and integrated dataset
* Comprehensive exploratory data analysis
* Restaurant performance dashboard
* Machine Learning forecasting models
* LSTM forecasting model
* RMSE and MAPE performance comparison
* Future sales forecasts
* Business recommendations based on findings

---

## Repository Structure

```text
Sales-Forecasting/
│
├── data/
│   ├── restaurants.csv
│   ├── items.csv
│   └── sales.csv
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_machine_learning_models.ipynb
│   └── 04_lstm_forecasting.ipynb
│
├── models/
│
├── visualizations/
│
├── forecasts/
│
├── requirements.txt
│
└── README.md
```

---

## Key Business Questions Answered

* Which restaurant generates the highest sales?
* Which items are most popular across all restaurants?
* What seasonal patterns exist in customer demand?
* Which restaurant generates the highest revenue?
* Does higher sales volume always lead to higher profitability?
* Which forecasting model performs best?
* What are the projected sales for the upcoming year?

---

## Author

**Eshaan Yadav**
AIML Capstone Project – Sales Forecasting using Machine Learning and Deep Learning

---

### Reference

Project requirements, datasets, objectives, and forecasting tasks are derived from the AIML Capstone project documentation. 

