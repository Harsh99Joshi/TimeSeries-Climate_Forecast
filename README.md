# TimeSeries-Climate_Forecast

# Climate Data Prediction using LSTM and other Models
This project uses the Jena climate dataset to predict temperature and pressure values based on historical climate data. The dataset is analyzed using various machine learning models, including LSTM (Long Short-Term Memory), GRU (Gated Recurrent Unit), and Conv1D (1D Convolutional Neural Network).

# Project Overview
The project aims to forecast the temperature and pressure of the Jena climate data over time using several deep learning architectures. The data contains climate features such as temperature, pressure, humidity, and wind speed, recorded every 10 minutes over several years.

# Key Models Implemented
# LSTM Model
A Long Short-Term Memory (LSTM) network is used to model sequential time-series data. This model is trained to predict only the temperature based on cyclical features representing day and year cycles.

# GRU Model
A Gated Recurrent Unit (GRU) model is another sequential model that is used for the same task as LSTM but with a different architecture, often proving to be more efficient.

# Conv1D Model
A 1D Convolutional Neural Network (Conv1D) model is applied to time-series forecasting, focusing on detecting patterns in time-based data.

# Multivariate Models
Models that predict both temperature and pressure by using multiple features from the dataset, employing either LSTM, GRU, or Conv1D layers.

# Hybrid Model
A combination of LSTM layers with Conv1D, aimed at capturing both local temporal features and global trends in the data.

# Dataset
The dataset used in this project is the Jena Climate Dataset, which contains measurements taken every 10 minutes from the year 2009 to 2016 in Jena, Germany. The data includes features like:

Temperature (°C)
Pressure (mbar)
Humidity (%)
Wind Speed (m/s)
and more...
Dataset Source
The dataset can be downloaded from:
[The Jena Climate Dataset on Kaggle](https://storage.googleapis.com/tensorflow/tf-keras-datasets/jena_climate_2009_2016.csv.zip)

After downloading, extract the dataset into your project directory for easy access.
