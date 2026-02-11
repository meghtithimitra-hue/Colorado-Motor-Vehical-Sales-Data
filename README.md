# Colorado-Motor-Vehical-Sales-Data
Exploratory data analysis, statistical testing, machine learning, and time-series forecasting on Colorado motor vehicle sales data (2008–2015).

Overview
An end-to-end data science project analyzing quarterly motor vehicle sales across Colorado counties from 2008 to 2015. The project covers exploratory data analysis, statistical testing, machine learning regression, and time-series forecasting (ARIMA, SARIMA) to understand trends, seasonality, and post-recession growth patterns.

What This Project Does
Performs EDA to explore regional and temporal sales patterns
Analyzes trend and seasonality, including the 2008–09 recession impact
Runs statistical tests (correlation, ANOVA, pre/post-2011 t-test)
Builds a Random Forest regression model for sales prediction
Applies ARIMA and SARIMA models for time-series forecasting
Compares models and selects SARIMA for realistic seasonal forecasts

Data
Scope: Quarterly motor vehicle sales by county in Colorado
Period: 2008 Q1 – 2015 Q4
Features: Year, Quarter, County, Sales (USD)

Key Insights
Clear decline around 2009 followed by strong growth after 2011
Arapahoe, El Paso, Jefferson, Adams are top contributing counties
Moderate but consistent quarterly seasonality (higher in later quarters)
Random Forest RMSE: ~20M (limited by few features)
SARIMA captures both trend + seasonality better than ARIMA
Forecast suggests continued growth to ~4.1–4.7B USD in quarterly sales

Tools
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
SciPy, statsmodels
Google Colab

Running the Project
Open the notebook in Google Colab and run all cells to reproduce the analysis.
If the notebook preview doesn’t render on GitHub, please download it or open it in Google Colab.

Why This Project Matters
This project demonstrates practical skills in:
Data analysis & visualization
Statistical reasoning
Machine learning regression
Time-series forecasting
Communicating insights from real-world data
