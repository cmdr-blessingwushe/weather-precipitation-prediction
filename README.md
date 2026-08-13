# Weather Precipitation Prediction

## Overview

A machine learning project investigating the prediction of daily
precipitation using historical London weather data.

The project uses linear regression and evaluates the effects of
feature transformation, feature selection, and statistical
outlier detection on model performance.

## Objective

The objective is to build a predictive model for precipitation
and investigate how different data-processing strategies affect
predictive performance.

## Methodology

The project follows the following pipeline:

1. Load and clean the weather dataset
2. Split the data into training and testing sets
3. Establish a baseline linear regression model
4. Compare feature transformation techniques
5. Perform Pearson correlation-based feature selection
6. Detect and remove statistical outliers
7. Train the final model
8. Evaluate performance using R²

## Machine Learning Techniques

- Linear Regression
- Min-Max Scaling
- Z-Score Standardization
- Row-wise Normalization
- Pearson Correlation
- Feature Selection
- Z-Score Outlier Detection
- Train/Test Evaluation

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Results

The project evaluates model performance at each stage of the
pipeline and selects the best-performing configuration based
on R².

### Final Model

![Actual vs Predicted](actual_vs_predicted.png)

## Project Structure

```text
weather-precipitation-prediction/
├── README.md
├── weather_precipitation_prediction.ipynb
├── requirements.txt
├── .gitignore
└── actual_vs_predicted.png