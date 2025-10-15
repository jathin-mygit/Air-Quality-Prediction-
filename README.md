
# Air Quality Prediction Using Machine Learning <br>
📊 Project Overview<br>
This project implements a machine learning workflow to predict the Air Quality Index (AQI) for major Indian cities using multiple pollutant and environmental parameters. It follows all requirements specified by INLIGHN TECH for educational, research, or demo use, and is fully compatible with Google Colab.

# Features <br>
Complete data preprocessing pipeline for air quality data <br>

Missing value handling (marked as -200 → imputed with mean) <br>

Multiple model comparison: Random Forest, Linear Regression, SVR <br>

Feature correlation & importance analysis <br>

Visualization suite: distributions, missing values, prediction performance <br>

Easy export of all results (CSV) <br>

Detailed metrics reporting (MAE, RMSE, R²) <br>

Jupyter Notebook (.ipynb) ready for Colab <br>

Synthetic realistic dataset for demonstration <br>

# Dataset Information <br>
Filename: air_quality_dataset.csv <br>

Rows: 8,760 (12 cities, daily data for 2 years) <br>

Columns: <br>

city, date, aqi (target) <br>

co, no, no2, o3, so2, pm2_5, pm10, nh3 <br>
 
Time Range: 2022-01-01 to 2023-12-31 <br>

Missing Values: ~2% of pollutant entries (-200) as per requirements <br>
# How to Run
Open Google Colab and upload Air_Quality_Prediction_Project.ipynb and air_quality_dataset.csv.

Run cells sequentially. Code is modular and well-commented.


