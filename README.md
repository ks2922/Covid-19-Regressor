# COVID-19 Hospitalisation and Mortality Prediction

This project uses publicly available data to predict COVID-19 hospital bed requirements and deaths in the UK at 1–4 week horizons, using machine learning and statistical analysis.

## Overview

During the pandemic, timely predictions of hospitalisation and mortality were crucial for managing healthcare resources. This project integrates multiple datasets—UK government COVID-19 data and Google mobility data—to model how changes in behaviour and infection trends affect hospitalisation and mortality rates.

## Key Features

Data preprocessing: Cleaned and smoothed time-series data, accounted for weekend effects and reporting delays.

Feature engineering: Included time-lagged variables to capture delayed effects of behaviour on hospitalisations and deaths.

Machine learning models: Explored multiple models, including linear regression, tree-based methods, and neural networks, with hyperparameter tuning.

Rolling predictions: Used a rolling-window approach to make forecasts throughout the pandemic period.

Performance evaluation: Quantified predictive accuracy using relevant metrics, achieving ~90% assignment accuracy with the best model.

## Technologies

Python, pandas, NumPy, scikit-learn, matplotlib
