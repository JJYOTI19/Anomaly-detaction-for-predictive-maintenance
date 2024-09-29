{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "ea93761f-2025-4a2a-adbf-4160dcce16c2",
   "metadata": {},
   "source": [
    "# Random Forest Model for Anomaly Detection\n",
    "\n",
    "This project implements an Anomaly Detection model using a Random Forest Classifier. The goal is to predict whether an anomaly has occurred in a given dataset based on a series of features.\n",
    "\n",
    "## Table of Contents\n",
    "\n",
    "1. Project Overview\n",
    "2. Dataset\n",
    "3. Model\n",
    "4. Results\n",
    "5. Installation\n",
    "6. Usage\n",
    "7. Contributing\n",
    "\n",
    "## Project Overview\n",
    "\n",
    "The objective of this project is to build a classification model to detect anomalies in time series data, with the target label being either 1 (anomaly) or 0 (normal).\n",
    "\n",
    "## Key Features:\n",
    "\n",
    "- Performed data preprocessing including handling missing values and irrelevant columns.\n",
    "- Trained a Random Forest Classifier to predict anomalies.\n",
    "- Achieved high accuracy in detecting anomalies.\n",
    "\n",
    "## Dataset\n",
    "\n",
    "The dataset contains time-series data with multiple features. The key columns include:\n",
    "\n",
    "- time: Timestamp of each data point.\n",
    "- y: Target column (1 = anomaly, 0 = normal).\n",
    "- x1, x2, ..., x60: Feature columns.\n",
    "\n",
    "## Model\n",
    "\n",
    "The model used is a Random Forest Classifier from Scikit-learn. The Random Forest is an ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction.\n",
    "\n",
    "## Key Libraries:\n",
    "- scikit-learn\n",
    "- pandas\n",
    "- numpy\n",
    "\n",
    "### Steps:\n",
    "\n",
    "1. Data Preprocessing:\n",
    "- Removed irrelevant columns and handled missing data.\n",
    "- Split the dataset into training and testing sets.\n",
    "\n",
    "2. Model Training:\n",
    "- A Random Forest Classifier was trained on the dataset using the fit() method.\n",
    "\n",
    "3. Evaluation:\n",
    "- The model was evaluated using accuracy and other metrics.\n",
    "\n",
    "## Results\n",
    "\n",
    "The model achieved an accuracy of 100% on the test dataset. The Random Forest model performed very well in identifying anomalies in the dataset."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "9a2fa87d-389b-424c-978a-610f9b7cf39d",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
