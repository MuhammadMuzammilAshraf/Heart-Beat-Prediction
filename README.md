# Time Series Analysis: Heart Rate Prediction
This repository contains code for performing time series analysis on heart rate data. The data is loaded from the train.csv file, and various time series techniques are applied to analyze and predict heart rate values.
## Project Structure
The project is organized as follows:

trainrain.csv: The dataset containing heart rate data over time.
Time Series.ipynb: Jupyter Notebook containing the entire time series analysis pipeline.
requirements.txt: File listing the project's dependencies. You can use this file to install the required libraries.

## Data Analysis and Preprocessing
The Time Series.ipynb notebook starts with data analysis and preprocessing. It includes steps to clean the data, remove irrelevant columns, and detect and remove outliers.

## Time Series Visualization
The notebook then visualizes the heart rate data over time using matplotlib. It shows a line plot of heart rate values and their corresponding timestamps.

## Exponential Smoothing
The project uses simple exponential smoothing from the statsmodels library to model and forecast the heart rate values. It fits two different models with different smoothing levels and visualizes the results.

## Differencing for Stationarity
To make the data stationary, the notebook performs differencing by subtracting each heart rate value from its previous value. The Dickey-Fuller test is then used to check for stationarity.

## Auto-regressive Model
The notebook uses an auto-regressive model to analyze the autocorrelation of the time series. It plots the autocorrelation and partial autocorrelation functions to determine the order of the model.

## SARIMAX Model
The notebook fits a Seasonal Autoregressive Integrated Moving Average with eXogenous regressors (SARIMAX) model to the heart rate data. It uses the statsmodels library for this purpose.

## Model Evaluation
The trained SARIMAX model is evaluated on a test set, and performance metrics, such as Mean Square Error (MSE) and Mean Absolute Error (MAE), are calculated and displayed.

## Heart Rate Prediction
Finally, the notebook predicts heart rate values for the next twenty minutes using the trained SARIMAX model. The predictions are visualized and compared to the actual heart rate values.

## Conclusion
This project demonstrates various time series analysis techniques, including data preprocessing, visualization, and modeling, to predict heart rate values. Feel free to explore the code, modify the models, and experiment with different time series forecasting approaches.

For any questions or feedback, please don't hesitate to contact the project owner.
