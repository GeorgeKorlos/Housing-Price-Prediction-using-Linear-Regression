# Capstone Project: Housing Price Prediction using Linear Regression

## Overview
This repository contains the capstone project for the Data Science track of Angela Yu's 100 Days of Python course. The goal of this project is to predict housing prices using various features of the houses. The project employs linear regression models, including transformations of the target variable for improved accuracy.

## Project Structure
- `housing_price_prediction.ipynb`: A Jupyter Notebook containing the complete analysis, data preprocessing, model training, and evaluation.
- `housing_price_prediction.py`: The corresponding Python script that runs the same analysis as the Jupyter Notebook.

## Data Description
The dataset used in this project includes various features related to housing, such as:
- Number of rooms (RM)
- Distance to employment centers (DIS)
- Student-teacher ratio (PTRATIO)
- Proximity to the river (CHAS)
- Pollution levels (NOX)
- Percentage of lower status of the population (LSTAT)
- And others...

## Key Steps in the Project
1. Data Exploration and Preprocessing
   - Analysis of the dataset for missing values and outliers.
   - Feature engineering and transformations.

2. Model Training and Evaluation
   - Implementation of linear regression models on both original and log-transformed target variables.
   - Evaluation of model performance using R-squared metrics on both training and test datasets.

3. Visualization
   - Scatter plots of actual vs. predicted prices.
   - Residual analysis to assess model fit.

4. Predictions
   - Estimating property values using the trained model with average property characteristics and custom-defined properties.

## Installation
To run this project, ensure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

You can install them via pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Usage

Open the Jupyter Notebook in your local environment or run the Python script to see the housing price prediction model in action.

## License

This project is for educational purposes as part of Angela Yu's 100 Days of Python course and is not intended for commercial use.
