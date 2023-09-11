# Heart Rate Prediction using Time Series Analysis

## Introduction
Sudden variations in heart rate can pose serious health risks, including stroke, heart failure, and sudden cardiac arrest. This project focuses on leveraging time series analysis and AI techniques to predict heart rate, enabling early detection and treatment of health issues. In this README, we provide a step-by-step guide on how to build a heart rate prediction model using Python and time series analysis.

## Dependencies
Before running the code, make sure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- statsmodels
You can install these dependencies using pip


## Dataset
We use a dataset collected from medical sensors, containing approximately four hours of heart rate data for a patient. The dataset includes timestamps and heart rate values. To maintain data privacy, we have not provided the dataset here, but you can replace `PT_Train.csv` with your own dataset or obtain a similar dataset from a relevant source.

## Data Preprocessing
- We perform data cleaning by removing irrelevant columns.
- We detect and remove outliers to ensure data quality.
- We check for missing values in the dataset.

## Model Building
- We use the Augmented Dickey-Fuller test to check for stationarity.
- We apply differencing to make the data stationary.
- We visualize autocorrelation and partial autocorrelation plots to determine model parameters.
- We build a SARIMAX model with appropriate parameters.

## Model Evaluation
- We evaluate the model's performance using metrics such as RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and MSE (Mean Squared Error).

## Future Work
There is room for improvement in this project. Future work may include:
- Exploring different time series models for better predictions.
- Incorporating more features and external data sources to enhance accuracy.
- Developing a user-friendly interface for healthcare professionals to use the model.

---

To predict heart rate for the next 20 minutes, you can use the provided code in your preferred Python environment. The results will help in early detection and monitoring of heart rate variations.
