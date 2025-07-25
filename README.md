📊 Comparative Analysis of GDP Forecasting Models on BRICS Nations
This project was undertaken as part of my Master’s thesis to analyze and forecast the GDP of BRICS nations (Brazil, Russia, India, China, and South Africa) using various time series and machine learning models. The primary objective was to evaluate the forecasting accuracy and robustness of traditional, hybrid, and deep learning approaches over a long time span (1980–2023) using World Bank datasets and exogenous economic indicators.

🔍 Objectives:
Forecast GDP trends for BRICS countries using historical economic data.

Compare the performance of three models:

SARIMAX

Hybrid SARIMAX + XGBoost

LSTM (Long Short-Term Memory)

Analyze model accuracy, interpretability, and ability to capture nonlinear patterns.

🛠️ Tools & Technologies:
Languages: Python

Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, XGBoost, TensorFlow/Keras, SHAP

Platform: Jupyter Notebooks

📈 Methodology:
Data Preprocessing: Cleaned and normalized GDP and economic indicator datasets (e.g., inflation rate, FDI, exports).

Feature Engineering: Lag features, growth rates, residuals for hybrid modeling.

Modeling:

SARIMAX for linear trend and seasonality.

XGBoost on SARIMAX residuals for boosting nonlinearity.

LSTM for learning long-term temporal dependencies in sequence data.

Evaluation Metrics: MAE, RMSE, MSE, AIC, BIC, R², and SHAP values for interpretability.

✅ Outcomes:
The Hybrid SARIMAX-XGBoost model achieved the best forecasting accuracy, combining interpretability with predictive power.

LSTM performed well on complex patterns but required careful tuning and more computational resources.

The study highlights the importance of hybrid modeling for real-world economic forecasting.
