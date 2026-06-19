# Port Operations Automation using Deep Learning

## Project Overview

This project was completed as part of the **Deep Learning Course-End Project**. The objective is to develop an automated boat classification system for port operations using computer vision and deep learning techniques.

Marina Pier Inc. aims to reduce operational errors caused by manual boat identification by implementing an intelligent image classification system capable of recognizing different types of boats entering the port. The project explores both a custom Convolutional Neural Network (CNN) and a lightweight Transfer Learning approach suitable for deployment on mobile devices.

---

## Problem Statement

Port operations often rely on manual classification of vessels, which can lead to human errors and operational inefficiencies.

The goal of this project is to:

* Automatically classify boats using image data
* Reduce classification errors
* Build a robust deep learning solution
* Compare custom CNN and transfer learning approaches
* Develop a lightweight model suitable for mobile deployment

---

## Dataset Description

The dataset contains **1,162 labeled boat images** across 9 classes.

### Boat Categories

* Buoy
* Cruise Ship
* Ferry Boat
* Freight Boat
* Gondola
* Inflatable Boat
* Kayak
* Paper Boat
* Sailboat

Images are organized into class-specific directories for supervised image classification.

---

## Project Workflow

### 1. Data Preparation

* Train-Test Split
* Image Normalization
* Data Loading using ImageDataGenerator
* Batch Processing
* Validation Split

### 2. Custom CNN Model

A Convolutional Neural Network was built from scratch using Keras.

#### Architecture

* Conv2D (32 Filters) + MaxPooling
* Conv2D (32 Filters) + MaxPooling
* GlobalAveragePooling2D
* Dense Layer (128 Neurons)
* Dense Layer (128 Neurons)
* Softmax Output Layer (9 Classes)

#### Training Configuration

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metrics:

  * Accuracy
  * Precision
  * Recall
* Epochs: 20

---

### 3. Transfer Learning Model

A lightweight deep learning model was developed using MobileNetV2.

#### Architecture

* MobileNetV2 (Pre-trained Base Model)
* GlobalAveragePooling2D
* Dropout (0.2)
* Dense Layer (256 Neurons)
* Batch Normalization
* Dropout (0.1)
* Dense Layer (128 Neurons)
* Batch Normalization
* Dropout (0.1)
* Softmax Output Layer

#### Training Configuration

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metrics:

  * Accuracy
  * Precision
  * Recall
* Early Stopping
* Epochs: Up to 50

---

## Model Evaluation

Both models were evaluated using:

* Test Accuracy
* Precision
* Recall
* Confusion Matrix
* Classification Report
* Training and Validation Curves

### Visualizations

* Training Loss vs Epochs
* Training Accuracy vs Epochs
* Validation Loss vs Epochs
* Validation Accuracy vs Epochs
* Confusion Matrix Heatmap

---

## Comparative Analysis

The project compares:

| Model                         | Purpose                             |
| ----------------------------- | ----------------------------------- |
| Custom CNN                    | Baseline image classifier           |
| MobileNetV2 Transfer Learning | Lightweight mobile-ready classifier |

The comparison evaluates:

* Classification Performance
* Generalization Ability
* Training Efficiency
* Deployment Suitability
* Computational Requirements

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Deep Learning Concepts Applied

* Computer Vision
* Image Classification
* Convolutional Neural Networks (CNNs)
* Transfer Learning
* MobileNetV2
* Image Augmentation
* Early Stopping
* Model Evaluation
* Multi-Class Classification

---

## Repository Structure

```text
05-Port-Operations-Automation/
│
├── README.md
├── port_operations_automation.ipynb
├── boat_type_classification_dataset/
├── saved_models/
└── results/
```

---

## Key Learning Outcomes

This project provided practical experience in:

* Building CNN architectures from scratch
* Applying transfer learning techniques
* Image preprocessing and augmentation
* Multi-class image classification
* Deep learning model evaluation
* Mobile-ready AI deployment strategies

---

## Author

**Eshaan Yadav**

Deep Learning Course-End Project – IIT Kanpur AIML Program

