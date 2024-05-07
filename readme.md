# Stroke Prediction Project

This project involves using a collection of Python scripts to analyze and model stroke prediction data.

## Description

This repository includes a Python script that handles a variety of tasks associated with stroke prediction. The script imports necessary libraries, loads datasets, preprocesses data, visualizes data, and uses multiple machine learning models (Random Forest, LGBM, XGBoost) for predictions.

## How to Run the Script

1. Ensure you have all the required libraries installed. These include:

   - numpy
   - matplotlib
   - seaborn
   - sklearn
   - lightgbm
   - xgboost
   - pandas
   
2. Load the required datasets. The script expects two datasets:

   - A training dataset ('./playground-series-s3e2/train.csv')
   - A test dataset ('./playground-series-s3e2/test.csv')
   - A real world dataset ('./healthcare-dataset-stroke-data.csv')
   
3. Run the Python script. You can do this in a Python environment or Jupyter notebook. The script will load the data, preprocess it, perform exploratory data analysis, and then apply and evaluate several machine learning models.

