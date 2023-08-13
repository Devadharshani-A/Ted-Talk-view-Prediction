# Ted-Talk-view-Prediction
This repository contains a Python script for predicting TED Talk views based on various features using machine learning models. The models used in this script include Linear Regression, Decision Tree Regressor, and Random Forest Regressor.

## Table of Contents

-[Introduction](#introduction)
-[Installation](#installation)
-[Usage](#usage)
-[Data](#data)
-[Feature Engineering](#feature-engineering)
-[Model Training](#model-training)
-[Evaluation](#evaluation)
-[Conclusion](#conclusion)


## Introduction
This Python script is designed to predict the number of views for TED Talk videos based on a variety of features. The script utilizes machine learning models to make predictions and evaluate their performance.

## Installation
To run the script, you'll need the following dependencies:

Python (>= 3.6)
pandas
numpy
scikit-learn
nltk

You can install these dependencies using the following command:
pip install pandas numpy scikit-learn nltk

## Usage
Clone this repository to your local machine.
Make sure you have the required dataset (ted_talks_en.csv) in the specified location.
Run the script using the following command:

python ted_talk_prediction.py

The script will load the dataset, perform feature engineering, train different regression models, and evaluate their performance.

## Data
The script uses the TED Talk dataset (ted_talks_en.csv) containing various attributes of TED Talk videos, including features like speaker details, talk details, and linguistic characteristics. The goal is to predict the number of views based on these attributes.

## Feature Engineering
The feature engineering process includes:

Dropping unnecessary columns from the dataset.
Handling missing values and outliers.
Extracting date-related features.
Processing textual fields and categorizing them into different attractiveness levels.

## Model Training
The script trains three different regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
These models are trained on the preprocessed dataset and used to make predictions.

## Evaluation
The performance of each model is evaluated using the following metrics:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R-squared (R2) Score
Adjusted R-squared Score
The decision tree model demonstrates the highest score among the evaluated models.

## Conclusion
This Python script demonstrates how to preprocess data, engineer features, train regression models, and evaluate their performance for predicting the number of views for TED Talk videos. You can modify the script or experiment with different models to further improve the prediction accuracy.
