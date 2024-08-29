# Body Fat Prediction 

## Project Overview

This project aims to predict body fat percentage using various machine learning algorithms. The dataset includes various features such as age, weight, height, and body measurements, which are used to build and evaluate prediction models.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
- [Installation](#installation)
- [Evaluation Metrics](#evaluation-metrics)
 
## Features

- Predict body fat percentage based on input features including Body Mass Index(BMI).
- Models include Support Vector Machines (SVM), Random Forest, Linear Regression, Decision Tree, K-Nearest Neighbors (KNN), and XGBoost.

## Dataset

The dataset used for training and testing includes the following features:
- Age
- Weight 
- Height
- Neck
- Chest
- Abdomen
- Hip
- Thigh
- Knee
- Ankle
- Biceps
- Forearm
- Wrist
- BMI

### Kaggle Dataset

- **Dataset Name:** [Body Fat Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset)
- **Source:** Kaggle
- **Description:** This dataset contains various body measurements used to predict body fat percentage.

To use the dataset:
1. **Download the dataset** from Kaggle and place it in the `data` directory.
2. **Rename the file** to `bodyfat.csv` for consistency with the script.

## Algorithms Used

- **Support Vector Machines (SVM)**
- **Random Forest**
- **Linear Regression**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**

## Installation

To run this project, you need Google Colab , Python and the following packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `xgboost`
- `matplotlib`  
## Evaluation Metrics
The performance of the models is evaluated using the following metrics:

- `R-squared (R²)`
- `Mean Absolute Error (MAE)`
- `Mean Squared Error (MSE)`
- `Root Mean Squared Error (RMSE)`

 
**Best Model based on R² Score:** Random Forest

**Best Model - Random Forest Performance:**
- R² Score (%): 99.89%
- Mean Squared Error: 0.05
