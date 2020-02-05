---
title: "Detection of Cardiac Arrhythmia"
date: 2018-01-17
tags: [heart disease, data science, machine learning, plotting]
header:
  image: # "/images/perceptron/percept.jpg"
excerpt: "Heart Disease, Data Science, Machine Learning, Plotting"
mathjax: "true"
---

**Description:** Transformed data and tested supervised learning models in Python to solve a multi-class classification problem of detecting different kinds of [cardiac arrhythmia](https://archive.ics.uci.edu/ml/datasets/arrhythmia)
**Software:** Python 3.7 <br>
**Presentation:** Jupyter Notebook <br>
**Goal:** Develop predictive model to predict 4 classes of **Cardiac Arrhythmia** <br>
**Result:** Testing Accuracy > 80%<br>

## Tasks
1. Load Libraies
2. Load Data
3. Data Cleaning and Transformation <br>
&nbsp;&nbsp;&nbsp;&nbsp;    3.1 Renaming Columns <br>
&nbsp;&nbsp;&nbsp;&nbsp;    3.2 Missing Data Imputation <br>
&nbsp;&nbsp;&nbsp;&nbsp;    3.3 Column Dropping <br>
4. Exploratory Analysis<br>
&nbsp;&nbsp;&nbsp;&nbsp;   4.1 Histograms for Numeric Variables<br>
&nbsp;&nbsp;&nbsp;&nbsp;   4.2 Pie Charts for Categoric Variables<br>
&nbsp;&nbsp;&nbsp;&nbsp;   4.3 Correlation Plot <br>
&nbsp;&nbsp;&nbsp;&nbsp;   4.4 Histograms by Target Class<br>
5. Modeling<br>
&nbsp;&nbsp;&nbsp;&nbsp;    5.1 Train Test Splits<br>
&nbsp;&nbsp;&nbsp;&nbsp;    5.2 Baseline Model<br>
&nbsp;&nbsp;&nbsp;&nbsp;    5.3 Feature Selection<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      5.3.1 Univariate Feature Elimination<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      5.3.2 Recursive Feature Elimination<br>
&nbsp;&nbsp;&nbsp;&nbsp;    5.4 Grid Search and Cross Validation<br>
6. Final Model Results

## Additional Information

### Models tried:
1. Logistic Regression
2. K Nearest Neighbors
3. Gradient Boosting
4. Support Vector Machines
5. Decision Trees
6. Random Forests
7. XG Boost
8. Light GBM

### Boosting methods:
1. Ada boost
2. Bagging

### Validation techniques:
1. Cross Validation
2. Grid Search

### Evaluation metrics:
1. Accuracy
2. Area Under Curve

### Project Link: [GitHub](https://github.com/Rahulub3r/Detection-of-Cardiac-Arrhythmia)
