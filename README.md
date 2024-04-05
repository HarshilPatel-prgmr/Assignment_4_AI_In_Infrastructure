**Stock Price Prediction with LSTM**
This project involves predicting stock prices using Long Short-Term Memory (LSTM) networks. LSTM is a type of recurrent neural network (RNN) that is well-suited for sequence prediction problems such as time series forecasting.

**Project Overview**
The project consists of the following main steps:

**Data Collection:** Historical stock price data for multiple stocks is collected using the Yahoo Finance API (yfinance).

**Data Preprocessing:** The collected data is cleaned and preprocessed, including handling missing values, scaling, and splitting into training and validation sets.

**Model Building:** An LSTM model is constructed using the Keras library. The model is trained on the training data to learn the patterns in the stock price sequences.

**Model Evaluation:** The trained model is evaluated using the validation data to assess its performance in predicting stock prices.

**Visualization:** The predicted stock prices are visualized alongside the actual stock prices to analyze the model's performance.

**Model Saving:** The trained LSTM model is saved for future use.

**Create Prediction Dashboard:** Actual and predicted prices for multiple stocks were visualized, allowing users to compare and analyze trends.

**Prerequisites**
Before running the code, ensure you have the following dependencies installed:

matplotlib
sqlite3
pandas
numpy
scikit-learn
keras
yfinance
dash
plotly
