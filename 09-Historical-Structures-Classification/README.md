# AIML Capstone – Autonomous Driving & Tesla Autopilot Safety Analysis

## Project Overview

This capstone project focuses on two key applications of Artificial Intelligence and Machine Learning in the autonomous driving domain:

1. **Vehicle Detection using Computer Vision**

   * Develop a deep learning-based object detection model capable of identifying and localizing vehicles in road images.
   * Predict vehicle types and generate bounding boxes around detected vehicles.

2. **Tesla Autopilot Safety Analysis**

   * Analyze Tesla autopilot-related accident and fatality data.
   * Perform exploratory data analysis (EDA) to understand accident trends, fatalities, and autopilot-related incidents.

The project combines **Computer Vision**, **Deep Learning**, and **Data Science** techniques to address real-world challenges in autonomous transportation systems. 

---

## Business Context

### Part 1: Vehicle Detection

Autonomous Vehicles (AVs) and Intelligent Transport Systems (ITS) rely heavily on real-time vehicle detection and tracking. Accurate vehicle recognition helps improve:

* Traffic monitoring
* Vehicle counting
* Incident detection
* Autonomous navigation
* Road safety systems

The objective is to train a deep learning model that can:

* Detect vehicles in images
* Classify vehicle types
* Localize vehicles using bounding boxes

### Part 2: Tesla Autopilot Safety Analysis

Tesla's Full Self-Driving (FSD) and Autopilot systems have generated significant public interest regarding road safety.

This section investigates:

* Fatal accident trends
* Driver and occupant fatalities
* Cyclist and pedestrian involvement
* Vehicle collision patterns
* Verified autopilot-related deaths



---

## Project Structure

```text
AIML-Capstone/
│
├── Part1_Object_Detection/
│   ├── data/
│   ├── images/
│   ├── annotations/
│   ├── models/
│   ├── notebooks/
│   └── results/
│
├── Part2_Tesla_Safety_Analysis/
│   ├── data/
│   ├── notebooks/
│   ├── visualizations/
│   └── reports/
│
├── README.md
└── requirements.txt
```

---

# Part 1: Vehicle Detection

## Dataset

The dataset consists of images containing autonomous vehicles captured under varying environmental conditions. 

### Objectives

* Prepare image datasets for training
* Build an object detection model
* Train and validate the model
* Evaluate detection performance
* Run inference on unseen images

### Suggested Models

* YOLOv8
* Faster R-CNN
* SSD (Single Shot Detector)
* RetinaNet

### Evaluation Metrics

* mAP (Mean Average Precision)
* Precision
* Recall
* IoU (Intersection over Union)
* F1 Score

### Workflow

1. Data preprocessing
2. Annotation processing
3. Train-validation split
4. Model training
5. Hyperparameter tuning
6. Model evaluation
7. Inference testing

---

# Part 2: Tesla Autopilot Safety Analysis

## Dataset

Dataset: **Tesla-Deaths.csv** 

### Key Variables

| Variable                        | Description                       |
| ------------------------------- | --------------------------------- |
| Case#                           | Unique accident identifier        |
| Year                            | Year of accident                  |
| Date                            | Date of occurrence                |
| Country                         | Country where accident occurred   |
| State                           | State where accident occurred     |
| Description                     | Accident details                  |
| Deaths                          | Number of fatalities              |
| Tesla Driver                    | Indicates if Tesla driver died    |
| Tesla Occupant                  | Tesla occupant information        |
| Other Vehicle                   | Number of other vehicles involved |
| Cyclists/Peds                   | Cyclist or pedestrian involvement |
| Model                           | Tesla model involved              |
| Autopilot Claimed               | Whether autopilot was claimed     |
| Verified Tesla Autopilot Deaths | Verified autopilot fatalities     |
| Source                          | Source of accident report         |



---

## Analysis Tasks

### Data Cleaning

* Check data types
* Handle missing values
* Remove duplicates
* Drop irrelevant columns

### Exploratory Data Analysis

#### Temporal Analysis

* Events by year
* Events by month
* Events by day
* Trends over time

#### Geographic Analysis

* Events by country
* Events by state
* Regional hotspots

#### Fatality Analysis

* Number of deaths per accident
* Tesla driver fatalities
* Occupant fatalities
* Multi-fatality incidents

#### Vulnerable Road Users

* Cyclist fatalities
* Pedestrian fatalities
* Tesla-cyclist/pedestrian interactions

#### Vehicle Collision Analysis

* Frequency of collisions with other vehicles
* Accident severity patterns

#### Model Analysis

* Distribution of accidents across Tesla models
* Model-wise fatality comparison

#### Autopilot Analysis

* Verified autopilot-related deaths
* Comparison between autopilot and non-autopilot incidents
* Trend analysis of autopilot accidents



---

## Technologies Used

### Machine Learning & Deep Learning

* Python
* TensorFlow / Keras
* PyTorch
* OpenCV

### Data Analysis

* Pandas
* NumPy
* Scikit-learn

### Visualization

* Matplotlib
* Seaborn
* Plotly

### Development Environment

* Jupyter Notebook
* Google Colab
* VS Code

---

## Expected Outcomes

### Part 1

* A trained vehicle detection model capable of identifying and localizing vehicles accurately.
* Performance evaluation using standard object detection metrics.

### Part 2

* Comprehensive analysis of Tesla accident and fatality data.
* Insights into autopilot-related safety trends.
* Data visualizations and recommendations based on findings.

---

## Future Improvements

* Real-time vehicle detection on video streams
* Multi-class vehicle classification
* Traffic density estimation
* Accident risk prediction models
* Predictive analytics for autonomous vehicle safety

---

## Author

**Eshaan Yadav**
AIML Capstone Project – Autonomous Driving & Tesla Autopilot Safety Analysis

---

### Reference

Project requirements, business scenario, datasets, and tasks are based on the AIML Capstone project document. 
