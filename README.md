#  Time Series Analysis of Truck Sales — Forecasting with SARIMA

This project presents a complete time series analysis and forecasting study of monthly truck sales using statistical modeling techniques. The objective is to analyze historical patterns, identify trends and seasonality, and build forecasting models capable of predicting future sales behavior.

The project applies classical time series methodologies, including data transformation, stationarity analysis, and SARIMA modeling, to demonstrate practical forecasting workflows used in real-world business scenarios.

---

##  Project Overview

Time series forecasting plays an important role in data-driven decision making, particularly in domains such as supply chain management, production planning, and demand forecasting.

In this project, a historical dataset of monthly truck sales is analyzed to:

- Understand long-term trends and seasonal behavior
- Stabilize variance and prepare the data for modeling
- Identify appropriate model parameters
- Build and evaluate forecasting models
- Generate future sales predictions

The workflow follows a structured analytical approach from exploratory analysis to final forecasting.

---

##  Dataset Information

- **Source:** Kaggle
- **Variable:** Monthly truck sales
- **Time Period:** January 2003 – December 2014
- **Frequency:** Monthly observations
- **Total Observations:** 144
- **Missing Values:** None

The dataset exhibits clear trend and seasonal patterns, making it suitable for SARIMA-based forecasting.

---

##  Methodology

The analysis is conducted through the following steps:

1. **Data Loading and Visualization**
   - Initial exploration of sales evolution over time
   - Identification of trend and seasonal components

2. **Exploratory Time Series Analysis**
   - Trend analysis
   - Seasonality detection
   - Variance behavior observation

3. **Data Transformation**
   - Log transformation to stabilize variance
   - Differencing to achieve stationarity

4. **Stationarity Testing**
   - Statistical tests to confirm stationarity assumptions

5. **Model Selection**
   - Identification of ARIMA/SARIMA parameters
   - Analysis of ACF and PACF plots

6. **Model Training**
   - SARIMA model fitting
   - Residual diagnostics

7. **Forecasting**
   - Future truck sales prediction
   - Visualization of forecast results

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Statsmodels
- Jupyter Notebook

---

##  Results

The SARIMA model successfully captures both the seasonal structure and long-term trend present in the data. The resulting forecasts demonstrate the effectiveness of statistical time series models for predicting demand patterns in business contexts.

---

##  Possible Improvements

- Comparison with machine learning forecasting models
- Hyperparameter optimization
- Inclusion of external variables (economic indicators, fuel prices, etc.)
- Deployment as an interactive forecasting tool

---

##  License

This project was developed for educational and research purposes.
