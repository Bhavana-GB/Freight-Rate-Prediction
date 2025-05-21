# Forecasting Container Freight Prices using Time Series & Machine Learning

This project builds a robust forecasting pipeline for monthly ocean freight container prices using both classical time series models and modern machine learning techniques. The focus is on forecasting rates for 20ft and 40ft containers across major global trade lanes. Accurate freight forecasts are critical for global supply chain planning, cost optimization, and risk mitigation.
## Why This Matters

Container shipping rates have seen extreme volatility due to global disruptions like COVID-19, port congestion, and geopolitical events. Accurate forecasting can help shippers, policymakers, and logistics providers anticipate changes and respond effectively.

## Dataset

- **Source:** USDA Agricultural Marketing Service  
- **Link:** [USDA Container Ocean Freight Rates](https://agtransport.usda.gov/Container/Container-Ocean-Freight-Rates/dtp5-fwp8/about_data)  
- **Scope:** Monthly rates for 20ft, 40ft containers along global trade(LA, Chicago to Shangai) lanes(2012–Present)

## Methodology

- **Exploratory Analysis:** Trend, seasonality, and volatility inspection
- **SARIMA Modeling:** Captures autoregressive and seasonal patterns
- **Random Forest on SARIMA Residuals:** Models nonlinear external influences
- **LSTM:** Deep learning model for sequential pattern learning
- **Facebook Prophet:** Benchmarks trend/holiday/seasonality-aware forecasts

## Key Insights

- Clear annual seasonality and route-specific trends observed
- Hybrid SARIMA + RF model outperforms standalone baselines
- Future scope includes LSTM modeling and external drivers like oil prices

## Tools & Technologies

- Python, pandas, statsmodels, scikit-learn, Prophet, Matplotlib, Seaborn , TensorFlow , Numpy , Matplotlib
- Jupyter notebooks organized by phase: EDA → Modeling → Evaluation

