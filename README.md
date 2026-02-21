# Weather Trend Forecasting and Climate Analysis

## Project Summary

This project analyzes the Global Weather Repository dataset to forecast weather trends and explore environmental patterns across regions. The work covers data cleaning, exploratory analysis, time-series forecasting, anomaly detection, feature importance evaluation, and spatial analysis.

The goal was to demonstrate a complete data science workflow — from preprocessing to advanced modeling — while extracting meaningful climate and environmental insights.


### Data Cleaning & Preprocessing

* [x] Converted `last_updated` to datetime for time series analysis
* [x] Removed duplicate and redundant unit-based columns (mph, miles, Fahrenheit, etc.)
* [x] Handled missing values using interpolation and median imputation
* [x] Detected and treated outliers using IQR
* [x] Log-transformed skewed pollution variables
* [x] Reduced multicollinearity

### Exploratory Data Analysis

* [x] Temperature trend visualization
* [x] Precipitation distribution analysis
* [x] Correlation heatmaps (weather-only and cross-domain)
* [x] Seasonal and monthly trend analysis

### Model Building

* [x] Time-based train/test split
* [x] Built baseline forecasting model
* [x] Evaluated using MAE and RMSE


## Advanced Requirements

### Advanced EDA

* [x] Anomaly detection using IQR and Isolation Forest
* [x] Identified extreme pollution spikes and seasonal anomalies

Observation:
Pollution spikes are concentrated in specific geographic zones and high-density areas.


### Forecasting with Multiple Models

* [x] ARIMA
* [x] Prophet
* [x] XGBoost (lag-based ML model)
* [x] Model comparison using MAE and RMSE
* [x] Ensemble model (weighted average)

Result:
The ensemble model improved predictive accuracy compared to individual models.

Final Results:
MAE: [Insert value]
RMSE: [Insert value]


### Climate Analysis

* [x] Monthly aggregation
* [x] Rolling averages (12-month trend)
* [x] Regional temperature comparisons

Observation:
Long-term temperature trends vary significantly by latitude and region.

---

### Environmental Impact Analysis

* [x] Cross-correlation between air quality and weather variables
* [x] Scatter-based relationship analysis

Key Findings:

* Wind reduces particulate concentration.
* Higher temperatures increase ozone levels.
* Humidity impacts pollution dispersion.

---

### Feature Importance

* [x] Random Forest importance
* [x] XGBoost importance
* [x] Permutation importance
* [x] Cross-method comparison

Observation:
Latitude and UV index consistently rank as the most important predictors of temperature.
Pressure and humidity contribute moderately.
Wind and precipitation have lower predictive influence.

---

### Spatial Analysis

* [x] Geographic scatter visualization
* [x] Country-level aggregation
* [x] Pollution distribution mapping

Observation:
Clear geographic clustering of pollution and temperature patterns is visible across continents.

---

# Technical Stack

Python
Pandas
NumPy
Matplotlib / Seaborn
Statsmodels (ARIMA)
Prophet
XGBoost
Scikit-learn
SHAP

---

# Key Takeaways

* Careful preprocessing significantly reduced multicollinearity.
* Geographic variables play a dominant role in temperature prediction.
* Ensemble forecasting outperformed standalone models.
* Weather parameters strongly influence air quality trends.
* Spatial analysis reveals clear environmental pattern clustering.

---

# How to Run

1. Install dependencies from `requirements.txt`
2. Run notebooks in order:

   * Data Cleaning
   * EDA
   * Forecasting
   * Advanced Analysis

---

# Repository Link

[Insert GitHub link here]

---

If you would like, I can also:

* Make a slightly more executive-facing version (for recruiters)
* Or compress this to a 1-page portfolio summary version for quick review
