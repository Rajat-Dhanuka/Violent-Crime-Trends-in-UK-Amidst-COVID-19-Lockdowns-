# Crime Data Analysis and Forecasting using PySpark and Time Series Models

## Overview
This project utilizes PySpark for data preprocessing and Spark SQL for data filtering to analyze historical crime data. The analysis includes exploratory data analysis (EDA) and data filtering to understand patterns in crime rates. Additionally, the project employs time series models, including ARIMA, SARIMA, and LSTM, to forecast violent crime rates during the April 2020 lockdown period.

## Contents
- **Data Preparation with PySpark**: Utilizes PySpark for data preprocessing tasks such as downloading crime data from Azure Storage, filtering out unnecessary columns, and handling missing values.
- **Exploratory Data Analysis (EDA) with Spark SQL**: Employs Spark SQL functions to conduct EDA, including aggregating crime data by crime type and month to identify patterns and trends.
- **Model Training and Forecasting**: Trains time series models (ARIMA, SARIMA, LSTM) to forecast violent crime rates. ARIMA and SARIMA models are trained using statsmodels, while LSTM model training is done using TensorFlow/Keras.
- **Evaluation and Comparison**: Evaluates the performance of each model using root mean squared error (RMSE) and compares their accuracy in predicting crime rates during the lockdown period.

## Installation
To run the project, make sure you have the necessary dependencies installed:
```bash
!pip install pyspark azure-storage-blob
```
Additionally, ensure you have access to the Azure Storage account containing the crime data.

## Usage
1. Use PySpark to download the crime data from Azure Storage and preprocess it.
2. Utilize Spark SQL for data filtering and conducting exploratory data analysis to understand crime patterns.
3. Train ARIMA, SARIMA, and LSTM models to forecast violent crime rates during the lockdown period.
4. Evaluate the models' performance using RMSE and compare their predictions.

## Acknowledgements
- The project was inspired by the need to analyze and forecast crime rates, especially during significant events like the April 2020 lockdown.
