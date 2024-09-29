# Random Forest Model for Anomaly Detection
This project implements an Anomaly Detection model using a Random Forest Classifier. The goal is to predict whether an anomaly has occurred in a given dataset based on a series of features.

## Table of Contents
1. Project Overview
2. Dataset
3. Model
4. Results
5. Installation
6. Usage
7. Contributing

## Project Overview

The objective of this project is to build a classification model to detect anomalies in time series data, with the target label being either 1 (anomaly) or 0 (normal).

## Key Features:
- Performed data preprocessing including handling missing values and irrelevant columns.
- Trained a Random Forest Classifier to predict anomalies.
- Achieved high accuracy in detecting anomalies.

## Dataset

The dataset contains time-series data with multiple features. The key columns include:

- time: Timestamp of each data point.
- y: Target column (1 = anomaly, 0 = normal).
- x1, x2, ..., x60: Feature columns.


## Model

The model used is a Random Forest Classifier from Scikit-learn. The Random Forest is an ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction.

## Key Libraries:
- scikit-learn
- pandas
- numpy
  
## Steps:
### 1. Data Preprocessing:
- Removed irrelevant columns and handled missing data.
- Split the dataset into training and testing sets.
### 2. Model Training:
- A Random Forest Classifier was trained on the dataset using the fit() method.
### 3. Evaluation:
- The model was evaluated using accuracy and other metrics.

## Results

The model achieved an accuracy of 100% on the test dataset. The Random Forest model performed very well in identifying anomalies in the dataset.
