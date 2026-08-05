# Air Quality Forecasting

## Overview

This project was developed as part of Smart India Hackathon (SIH) 2025 to forecast ground-level air pollutant concentrations using machine learning techniques. The project integrates meteorological observations, Chemical Transport Model (CTM) forecasts, and site-specific environmental data to predict concentrations of Ozone (O₃) and Nitrogen Dioxide (NO₂).

The solution focuses on improving forecast accuracy through feature engineering, bias correction, and gradient boosting models.


## Problem Statement

Accurate forecasting of air pollutants is essential for environmental monitoring and public health planning. Traditional forecasting methods often struggle with spatial and temporal variability.

This project aims to improve prediction accuracy by combining multiple environmental data sources with machine learning models.


## Objectives

- Forecast hourly concentrations of O₃ and NO₂.
- Improve prediction accuracy using engineered features.
- Apply bias correction to CTM forecast data.
- Optimize model performance through hyperparameter tuning.
- Generate predictions for multiple monitoring sites.


## Methodology

The project consists of the following stages:

1. Data preprocessing
2. Feature engineering
3. CTM bias correction
4. Satellite-based feature adjustment
5. Lag feature generation
6. Model training using CatBoost
7. Hyperparameter optimization using Optuna
8. Prediction generation
9. Model evaluation


## Technologies Used

- Python
- Polars
- NumPy
- CatBoost
- Scikit-learn
- Optuna
- Jupyter Notebook


## Features

- Multi-site air quality forecasting
- Feature engineering for environmental data
- CTM bias correction
- Lag-based feature generation
- K-Fold cross-validation
- Hyperparameter optimization
- Automated prediction generation for unseen datasets


## Dataset

The project uses site-wise datasets containing:

- Historical pollutant observations
- Meteorological variables
- CTM forecast data
- Geographic site information

Training and unseen input datasets are provided separately for each monitoring site.


## Results

The trained models generate pollutant concentration forecasts for unseen data across multiple monitoring locations. Model performance is evaluated using standard regression metrics during training and validation.


## Future Improvements

- Deploy the forecasting model as a web application.
- Incorporate additional satellite datasets.
- Explore deep learning models for time-series forecasting.
- Enable real-time prediction using live environmental data.


## Team

This project was developed collaboratively as part of Smart India Hackathon (SIH) 2025.

