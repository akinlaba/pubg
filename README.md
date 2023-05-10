## Introduction

Leveraging data from [pubg hosted competition on Kaggle](https://www.kaggle.com/competitions/pubg-finish-placement-prediction), the goal of this project is to - 

  1. Explore the dataset 
  2. Predict finish placement from players given features tracked per session for each player 
  3. Feature engineer and show how the right feature engineering can impact the performance of models

The repository holds 3 Jupyter Notebooks -
  1. eda - This notebook explores the data, visualizes and highlights different statistical attributes
  2. Baseline Model Analysis - Models are built without any feature engineering as a benchmark in this notebook
  3. feature engineering - Features are engineered using my knowledge of first person shooters and inspiration from other studied works
  4. model analysis with engineered features - Models are built with engineered features

Models used in this project include -
  a. Linear Regression
  b. Lasso
  c. Ridge
  d. Random Forest Regressor
  e. Ada Boost Regressor
  f. Gradient Boost Regressor
