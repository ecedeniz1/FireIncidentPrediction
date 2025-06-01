# Fire Incident Prediction in İzmir (DI501 Term Project)

This repository presents a comprehensive analysis of urban fire patterns in İzmir, Turkey, using both statistical techniques and machine learning models. The study addresses spatial inequalities in fire response and builds a predictive model for daily fire incident forecasting.

## Research Questions

1. What are the seasonal, geographical, and causal patterns of fire incidents in İzmir during 2023, and how are these patterns influenced by socioeconomic indicators such as neighborhood income levels and building structures?
2. Can a machine learning model be developed to accurately predict the daily number of fire incidents in İzmir, using spatial, temporal, and structural characteristics?

## Methods Overview

- **Statistical Analysis**: Chi-square test, survival analysis, Kruskal-Wallis H test
- **Predictive Modeling**: Random Forest Regression, performance comparison via RMSE, MAE, R², and paired t-tests
- **Feature Engineering**: Extracted variables include temporal indicators, district-level aggregations, and dominant building types


## Key Findings

- Fire response times significantly vary between districts (Kruskal-Wallis p < 0.0001), indicating spatial inequality.
- A tuned Random Forest Regressor achieved **R² = 0.741** on the test set, and **cross-validated R² = 0.759**, showing strong predictive performance.
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





