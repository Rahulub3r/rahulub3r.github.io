---
title: "Predicting Molecular Properties"
date: 2019-08-30
tags: [regression, data science, machine learning, supervised learning]
header:
  image: # "/images/perceptron/percept.jpg"
excerpt: "Regression, Data Science, Machine Learning, Supervised Learning"
---

Molecular property called as **scalar coupling constant** is to be predicted from some geometric features of 100,000 plus organic molecules.
More details about the kaggle competition can be found [here](https://www.kaggle.com/c/champs-scalar-coupling)

**Software:** R <br>
**Output measure:** Testing MAE (Mean Absolute Error)<br>
**Tasks:** Regression, Feature Engineering, Data Transformation<br>
**Number of rows:** Train rows-4.5M; Test rows-2.5M<br>
**Models:** Linear Regression, Adaptive Regression Splines, Random Forest, Neural Nets, and LightGBM<br>

## F.A.Q
### How to run these scripts?

Run the load_data.R script to first load the data the way we want and then use the analysis.R script to run the code for modeling

### Where to get data?
The datasets are huge so, they have to be downloaded from kaggle

train.csv, test.csv, and structures.csv files should be downloaded from this [website](https://www.kaggle.com/c/champs-scalar-coupling/data)

geometric features should be downloaded from this [website](https://www.kaggle.com/bigironsphere/simple-molecular-geometry-features)

### NOTE: This scripts are not very organized and are still in the progress of getting better for re-use


### Project Link: [GitHub](https://github.com/Rahulub3r/Predicting-Molecular-Properties)
