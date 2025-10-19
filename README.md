This repository contains a comprehensive analysis of U.S. housing price dynamics using the Zillow Home Value Index (ZHVI) dataset spanning from 2000 to 2025. The project explores the impact of major economic shocks—the 2008 financial crisis and the COVID-19 pandemic—on housing price returns across different U.S. regions and cities. It combines exploratory data analysis (EDA), seasonal decomposition, and time-series forecasting to understand short-term and long-term trends.

Key steps include data preprocessing, feature engineering, and normalization to ensure the dataset is clean, consistent, and suitable for statistical analysis. Seasonal decomposition is performed to separate trend, seasonal, and residual components, highlighting structural changes caused by economic shocks. Stationarity is tested using the Augmented Dickey-Fuller (ADF) test.

The forecasting analysis compares ARIMA and SARIMA models, with SARIMA demonstrating superior performance in capturing seasonal patterns and predicting housing price trends. The model provides six-month forecasts for the top 20 most valuable U.S. regions, revealing variations in growth, resilience, and post-shock recovery.

The repository includes visualizations of national and regional trends, year-over-year growth, and predictive heatmaps. Insights demonstrate the heterogeneous impact of the two crises, the cyclical nature of housing prices, and the regions with robust growth versus minor declines.

Limitations and challenges are also discussed, including missing macroeconomic variables, nonlinear market dynamics, and model dependency on parameter tuning. This project serves as a foundation for understanding regional housing markets, supporting data-driven decision-making, and providing predictive insights for short-term housing price movements.

Key Features:

Time-series analysis of 3,073 U.S. counties

Seasonal decomposition of housing prices

Forecasting with ARIMA and SARIMA models

Regional and state-level insights

Visualization of national trends, seasonality, and forecasted prices
