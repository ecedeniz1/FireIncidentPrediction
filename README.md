# Fire Incident Prediction in İzmir (DI501 Term Project)

This repository presents a comprehensive analysis of urban fire patterns in İzmir, Turkey, using both statistical techniques and machine learning models. The study addresses spatial inequalities in fire response and builds a predictive model for daily fire incident forecasting.

## Research Questions

1. What are the temporal and spatial patterns of fire incidents in İzmir in 2023, and how do socioeconomic indicators (e.g., income levels, building types) influence fire incident rates?
2. Can machine learning techniques be used to forecast daily fire incident counts based on spatial, temporal, and urban features?

## Methods Overview

- **Statistical Analysis**: Chi-square test, survival analysis, Kruskal-Wallis H test
- **Predictive Modeling**: Random Forest Regression, performance comparison via RMSE, MAE, R², and paired t-tests
- **Feature Engineering**: Extracted variables include temporal indicators, district-level aggregations, and dominant building types


## Key Findings

- Fire response times significantly vary between districts (Kruskal-Wallis p < 0.0001), indicating spatial inequality.
- A tuned Random Forest Regressor achieved an **R² of 0.759**, predicting daily fire counts with strong accuracy.
- **Top predictive features**: `top_ilce_fire_count`, `month`, and `top_building_type`
- Resulting insights support more equitable and proactive emergency service planning.

## How to Run

1. Clone the repository:

git clone https://github.com/ecedeniz1/FireIncidentPrediction.git
cd FireIncidentPrediction

2. Install dependencies:

pip install -r requirements.txt

3. Launch the notebook:

jupyter notebook notebooks/ece_deniz_FireIncidentPrediction.ipynb





