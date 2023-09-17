
# Metro Train Dataset
> Data Mining Course Project-1

## Group-20 Data Pirates

## Description
> This MetroPT-3 Dataset contains readings from pressure, temperature, motor current, and air intake valves were collected from a compressor's Air Production Unit (APU) from a metro train. This dataset reveals real predictive maintenance challenges encountered in the industry. It consists of multivariate time series data obtained from several analog and digital sensors installed on the compressor of a train. The dataset have 1516948 data entries where each is described by 5 features from 7 analogue (1-7) and 8 digital (8-15) sensors.

## Use cases
> It can be used for failure predictions, anomaly detection and prediction, timeseries forecasting of the different readings using Data Mining topics and Models like linear and logistic regression.

## Table of Content:
### EDA(Exploratory data analysis)
>EDA is a crucial step in understanding the dataset, identifying patterns, and preparing the data for further analysis or modeling.

>Introduction to EDA for Pressure Columns and Sensors Data:
This dataset contains time-series data related to various pressure columns and sensors. The objective of this EDA is to gain insights into the dataset, identify potential issues, and prepare the data for subsequent tasks such as anomaly detection, predictive modeling  or system monitoring.
>Here's a breakdown of the key steps involved in the EDA process:
1. Data Loading
2. Data Overview
3. Data Cleaning
4. Data Visualisation
5. Feature Selection
6.Statistical Summary
7.Anomaly Detection
8.Correlation Analysis
9.Preprocessing
>
### Data Preprocessing
> We observed the correlation values among the features of the dataset, and we found a particular pair of features having value of correlation almost equal to 1. So, we removed one of those features which would reduce the model complexity.

> Extracting the columns of Month, Day, Hour, Minute, Second from the given timestamp to make bins of those fields and use them for further prediction.

> Creating Lag_1 variable(value of oil temperature after lag of 1 time period for time series analysis. 

> Another aspects of preprocessing include removing null values from the dataset if any, normalising the data for using in regression models

### Prediction
> Using IQR Analysis to label outliers in the given dataset and then using logistic regression to predict whether the new data points are Anomalies/Errors or not.

> Using the bins created using data preprocessing along with the features of the dataset, predicting the value of oil temperature for the new data points with linear regression.

> Using the lag_1 variable to make predictions about the value of oil_temperature with linear regression.

## Group Members:

Aayush Patel - 202101452 

Ayush Patel - 202101439

Varun Vyas - 202101468

Dhruvi Gohel - 202101188

Dhruvil Thakor - 202101462

## Acknowledgement

Dr. Arpit Rana
