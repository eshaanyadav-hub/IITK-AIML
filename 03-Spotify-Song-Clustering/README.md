# Spotify Song Clustering and Cohort Analysis

## Project Overview

This project was completed as part of the **Machine Learning Course-End Project**. The objective was to analyze Spotify song data and create cohorts of similar songs using clustering techniques. These cohorts can be used to improve recommendation systems by grouping songs with similar characteristics.

The dataset contains information from Spotify's API on albums and songs by **The Rolling Stones**, including various audio features, popularity metrics, and metadata.

---

## Problem Statement

Modern streaming platforms aim to provide personalized experiences by recommending content that aligns with user preferences. Spotify seeks to group similar songs into cohorts to enhance recommendation quality and user engagement.

The objective of this project is to:

* Explore and understand song characteristics
* Identify patterns influencing song popularity
* Apply dimensionality reduction techniques
* Perform cluster analysis to group similar songs
* Define meaningful song cohorts for recommendation purposes

---

## Dataset Description

The dataset contains Spotify API data for Rolling Stones albums and tracks.

### Key Features

* Song Popularity
* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo
* Duration
* Album Information
* Release Date

Each song is associated with a unique Spotify identifier.

---

## Project Workflow

### 1. Data Inspection and Cleaning

* Checked for duplicate records
* Identified and handled missing values
* Removed erroneous entries
* Investigated potential outliers
* Prepared data for analysis

### 2. Exploratory Data Analysis (EDA)

* Analyzed distributions of song features
* Compared album performance based on popular songs
* Explored relationships among audio characteristics
* Investigated how popularity varies across song attributes
* Studied trends in popularity over time

### 3. Feature Engineering

* Selected relevant variables
* Scaled numerical features
* Prepared data for clustering
* Evaluated feature importance

### 4. Dimensionality Reduction

* Applied dimensionality reduction techniques
* Reduced feature complexity while preserving information
* Visualized song similarities in lower-dimensional space

### 5. Cluster Analysis

* Determined the optimal number of clusters
* Applied clustering algorithms
* Segmented songs into distinct cohorts
* Interpreted cluster characteristics

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Techniques

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Feature Scaling
* Principal Component Analysis (PCA)
* K-Means Clustering
* Cluster Evaluation

---

## Key Outcomes

* Identified natural groupings of songs
* Created song cohorts for recommendation purposes
* Analyzed factors influencing song popularity
* Visualized relationships between audio features
* Demonstrated the role of clustering in recommendation systems

---

## Repository Structure

```text
03-Spotify-Song-Clustering/
│
├── README.md
├── spotify_song_clustering.ipynb
├── spotify_dataset.csv
└── supporting_files/
```

---

## Learning Outcomes

This project provided hands-on experience in:

* Unsupervised Machine Learning
* Cluster Analysis
* Recommendation System Foundations
* Feature Engineering
* Dimensionality Reduction
* Data Visualization
* Business-Oriented Data Science

---

## Author

**Eshaan Yadav**

Machine Learning Course-End Project – IIT Kanpur AIML Program

