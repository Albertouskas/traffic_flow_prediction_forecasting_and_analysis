# Traffic Forecasting with SHAP Explainability

## Overview

This project implements a complete workflow for traffic forecasting using machine learning and time series forecasting techniques. In addition to generating accurate traffic predictions, the project focuses on model interpretability through SHAP (SHapley Additive exPlanations), providing insights into the factors driving forecast outcomes.

Link to used dataset:https://www.kaggle.com/datasets/rauffauzanrambe/smart-city-traffic-flow-prediction-dataset

## Features

- Traffic volume forecasting
- Time series feature engineering
- Lag and rolling-window features
- Machine Learning-based forecasting models
- Model performance evaluation
- SHAP explainability analysis
- Global and local feature importance visualization

## Project Structure

├── data/ # Raw and processed datasets
├── notebooks/ # Exploratory analysis and experiments
├── src/
│ ├── preprocessing/
│ ├── feature_engineering/
│ ├── modeling/
│ ├── evaluation/
│ └── explainability/
├── models/ # Trained models
├── reports/ # Results and visualizations
└── README.md

## Methodology

The workflow follows these main steps:

1. Data collection and preprocessing
2. Feature engineering
3. Forecasting model training
4. Model evaluation
5. SHAP analysis
6. Results interpretation

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost / LightGBM
- SHAP
- Matplotlib
- Seaborn

## Example Outputs

### Forecasting

- Daily traffic predictions
- Multi-step forecasting
- Performance metrics (MAE, RMSE, MAPE)

### Explainability

- SHAP Summary Plot
- Feature Importance Analysis
- Individual Prediction Explanations
- Dependence Plots

## Installation

```bash
git clone https://github.com/<username>/traffic-forecasting-shap.git
cd traffic-forecasting-shap

pip install -r requirements.txt
