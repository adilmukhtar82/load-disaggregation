# Load Disaggregation Using Machine Learning

This repository contains the implementation of a load disaggregation framework using various machine learning models. The framework focuses on predicting appliance-level energy consumption from aggregated household energy data. By leveraging temporal dependencies, cyclic features, and advanced regression models, this project aims to address the challenges of energy disaggregation in real-world scenarios.

## Overview

### Objective

The primary goal of this project is to accurately predict the power consumption of individual appliances in a household using aggregated load data. This is achieved by:

- Implementing a sliding window approach to model temporal dependencies.
- Training and evaluating multiple machine learning models for multi-output regression.
- Visualizing and analyzing model performance using RMSE and MAE metrics.

### Key Features

- **Data Preprocessing:** Sliding window creation, cyclic feature engineering, and time-series data splitting for effective training and evaluation.
- **Model Training:** Training a range of regression models, including:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - XGBoost
  - Random Forest
  - Support Vector Machines (SVM)
  - Artificial Neural Networks (ANN)
- **Evaluation:** Comprehensive evaluation using RMSE and MAE metrics, with detailed visualizations of predictions vs. actuals.
- **Future Extensions:** Integration of semantic information (e.g., weather data, occupancy) and district-level disaggregation.
