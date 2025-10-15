<div align="center"><img src="https://img.shields.io/badge/Air%20Quality%20Prediction-Machine%20Learning-green?style=for-the-badge&logo=python"></div>
# Air Quality Prediction Using Machine Learning
📊 Project Overview
This project implements a machine learning workflow to predict the Air Quality Index (AQI) for major Indian cities using multiple pollutant and environmental parameters. It follows all requirements specified by INLIGHN TECH for educational, research, or demo use, and is fully compatible with Google Colab.

🚀 Features
Complete data preprocessing pipeline for air quality data

Missing value handling (marked as -200 → imputed with mean)

Multiple model comparison: Random Forest, Linear Regression, SVR

Feature correlation & importance analysis

Visualization suite: distributions, missing values, prediction performance

Easy export of all results (CSV)

Detailed metrics reporting (MAE, RMSE, R²)

Jupyter Notebook (.ipynb) ready for Colab

Synthetic realistic dataset for demonstration

📂 Dataset Information
Filename: air_quality_dataset.csv

Rows: 8,760 (12 cities, daily data for 2 years)

Columns:

city, date, aqi (target)

co, no, no2, o3, so2, pm2_5, pm10, nh3

Time Range: 2022-01-01 to 2023-12-31

Missing Values: ~2% of pollutant entries (-200) as per requirements
How to Run
Open Google Colab and upload Air_Quality_Prediction_Project.ipynb and air_quality_dataset.csv.

Run cells sequentially. Code is modular and well-commented.

**Ch
