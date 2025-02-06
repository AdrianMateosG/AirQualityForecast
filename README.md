# Air Quality Prediction in Monterrey

This repository contains the implementation and analysis of a predictive model addressing a critical environmental challenge: air pollution in Monterrey, Mexico. By utilizing advanced data science techniques and historical data spanning from January 2022 to July 2024, this project focuses on forecasting key air pollutants (PM10, SO2, CO, and NOX) to support informed decision-making and mitigate the adverse health effects associated with poor air quality.

## Project Objective

The primary objective of this project is to develop a reliable predictive model capable of estimating the concentrations of major air pollutants in Monterrey. Leveraging statistical analysis, feature engineering, and Long Short-Term Memory (LSTM) neural networks, the project identifies complex temporal patterns and correlations between pollutants and meteorological variables. This work lays a foundation for proactive air quality management and public health protection.

## Key Features

- **Data Preparation:**  
  Comprehensive preprocessing, including anomaly detection and removal, imputation of missing values using K-Nearest Neighbors (KNN), and aggregation to daily resolution.

- **Feature Engineering:**  
  Integration of additional explanatory variables such as holidays, weekends, and recurring temporal cycles (derived from periodograms) to enhance model accuracy.

- **Exploratory Data Analysis:**  
  Analysis of trends, seasonality, and key correlations through visualization and statistical tests (KPSS and ADF) to ensure data stationarity and robustness.

- **Model Implementation:**  
  Deployment of an LSTM neural network tailored to capture short- and long-term dependencies in time-series data, with an optimized architecture and fine-tuned hyperparameters.

## Acknowledgments

This project was originally developed as part of a group effort at Tecnológico de Monterrey. Special thanks to my teammates for their collaboration and contributions:

- José Antonio Torres Villegas  
- Juan Marco Castro Trinidad  
- Alexei Carrillo Acosta
- Adrian Mateos Garza (myself)
