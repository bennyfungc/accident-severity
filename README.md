# Accident Severity and Consequences Extrapolation based on Local/Historical Environment Characteristics

CMPE255 Data Mining Project

Our project aims to analyze data on traffic accidents and to build a model for predicting the severity of an accident based on potentially useful information, such as time of day, weather conditions, season of the year, etc.

---

## Authors

Chanip Chong - [chanip.chong@sjsu.edu](mailto:chanip.chong@sjsu.edu)

Jingjing Bu - [jingjing.bu@sjsu.edu](mailto:jingjing.bu@sjsu.edu)

William Su - [william.su@sjsu.edu](mailto:william.su@sjsu.edu)

Benny Fung - [benny.fung@sjsu.edu](mailto:benny.fung@sjsu.edu)

---

## Dataset

We make use of the following dataset with 4.2million records of traffic accidents in the US from February 2016 - December 2020:

https://www.kaggle.com/sobhanmoosavi/us-accidents

---

## How to run

Clone this repo / download each Jupyter Notebook file (.ipynb) and run the notebook. A subset of our dataset has been provided as `US_Accidents_Dec20.csv`.

- `Visualization.ipynb` was used for data exploration and creating useful visualizations of our dataset

- `lightgmbregressionsklearn.ipynb` focuses on our classification task using LightGBM

- `accident_regr_analysis.ipynb` focuses on using linear models for regression task & NN for regression and classification

- `gp.ipynb` focuses on using different models for classification.
