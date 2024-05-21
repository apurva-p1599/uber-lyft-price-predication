# Uber-Lyft-price-predication
## Overview
This project aims to apply machine learning techniques to analyze and predict metrics for ride-sharing services such as Uber and Lyft. The project involves data preprocessing, model training, and evaluation using various regression algorithms.

## Project Structure
The project includes the following steps:

#### Data Preprocessing
Splitting the data into training and testing sets.
Normalizing and transforming features using preprocessing pipelines.

#### Model Training
Implementing different regression models (KNN Regressor, Random Forest Regressor, Linear Regression) for Uber and Lyft datasets.
Training the models on the training data.

#### Model Evaluation
Predicting the target values on the test data.
Calculating evaluation metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) score.

## Installation
To run this project, you need to have Python and the following libraries installed:

numpy

pandas

scikit-learn

matplotlib

You can install the required libraries using pip:
pip install numpy pandas scikit-learn matplotlib

## Results
The models are evaluated based on their performance metrics.
1. Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values. Lower values indicate better model performance.
2. Root Mean Squared Error (RMSE): The square root of MSE, providing an error metric in the same units as the target variable. Lower values indicate better model performance.
3. R² Score (Coefficient of Determination): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables. Values closer to 1.0 indicate better model performance.
