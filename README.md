# House Price Prediction Project

## Overview

This project aims to predict house prices based on various features using machine learning techniques. We explore a dataset containing information about houses in King County, Washington, USA.

## Dataset

The dataset used in this project is obtained from [here](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction). This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

## Usage

To use the project, execute the main script:

`python house_price_prediction.ipynb`

This will load the dataset, preprocess it, train the machine learning model, and evaluate its performance.

## Models Used

- Linear Regression: Predict house prices based on individual features.
- Ridge Regression: Regularized linear regression to handle multicollinearity.
- Polynomial Regression: Extend linear regression with polynomial features to capture non-linear relationships.

## Evaluation

We evaluate the performance of each model using the R2 score, which measures the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Results

**Model Performance**

- Linear Regression: Achieved an R2 score of 65.76% on the test set.
- The Pipeline improved performance over linear regression with an R2 score of 75.13%
- Ridge Regression: Performed poorly with an R2 score of 64.78%.
- Polynomial Regression: Captured non-linear relationships, resulting in an R2 score of 70.02%.

## Future Work

- Model Refinement: Explore advanced machine learning techniques, such as ensemble methods and deep learning, to further improve predictive performance.
- Feature Engineering: Experiment with additional features or transformations to enhance model interpretability and generalization.
- Deployment: Deploy the trained model in a production environment for real-time predictions or integrate it into a web application for user interaction.
