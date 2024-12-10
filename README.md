# Load Disaggregation Using Machine Learning

This repository contains the implementation of a load disaggregation evaluation framework using various machine learning models. The framework focuses on predicting appliance-level energy consumption from aggregated household energy data. 

## Overview

### Objective

The primary goal is to accurately predict the power consumption of individual appliances in a household using aggregated load data. This is achieved by (so far):

- Implementing a sliding window approach to model temporal dependencies.
- Training and evaluating multiple machine learning models for multi-output regression.
- Visualizing and analyzing model performance using RMSE and MAE metrics.

### Key Features

- **Data preprocessing:** Sliding window creation, cyclic feature engineering, and time-series data splitting for effective training and evaluation.
- **Model training:** Training a range of regression models, including:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - XGBoost
  - Random Forest
  - Support Vector Machines (SVM)
  - Artificial Neural Networks (ANN)
- **Evaluation:** evaluation using RMSE and MAE metrics, with visualizations of predictions vs. actuals.

- **Future directions:** Integration of semantic information (e.g., weather data, occupancy, geospatial) and district-level disaggregation.
