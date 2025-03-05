# Tesla-Stock-Price-Prediction-Using-LSTM
 Use of LSTM to perform a stock market prediction on Tesla stock prices from January 2019 to October 2024


## 1. Introduction

The project aims to develop a deep learning-based predictive model for Tesla's stock prices using Long Short-Term Memory (LSTM) networks. Given the time-series nature of stock prices, LSTM, a specialized form of recurrent neural networks (RNNs), is well-suited to capture temporal dependencies and trends.

## 2. Objectives

1. To collect and preprocess Tesla stock price data from January 2019 to October 2024.

2. To design and implement an LSTM model for time-series forecasting of stock prices.

3. To evaluate the model’s predictive performance using relevant metrics.

4. To visualize the predicted trends against actual stock price movements.

5. To provide insights on potential improvements and limitations of using LSTM for stock price prediction.

## 3. Project Scope

### 3.1 Dataset and Preprocessing

1. Historical stock price data for Tesla (TSLA) will be sourced from Yahoo Finance or other financial APIs.

2. Key features will include Open, High, Low, Close (OHLC) prices, Volume, and additional technical indicators.

3. Data preprocessing steps will include normalization, handling missing values, and feature engineering.

4. The dataset will be split into training, validation, and test sets.

### 3.2 Model Development

1. An LSTM-based sequential model will be implemented using TensorFlow/Keras.

2. The model architecture will include LSTM layers, dropout layers to prevent overfitting, and dense layers for output prediction.

3. Hyperparameter tuning will be conducted for optimization.

### 3.3 Training and Evaluation

1. The model will be trained using historical stock price data.

2. Evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared will be used.


### 3.4 Prediction and Visualization

1. The trained LSTM model will predict future stock prices for Tesla.

2. Visualizations will include comparison plots of actual vs. predicted prices.

3. Trend analysis and insights will be presented.

## Data Procurement

Data was collected from Yahoo Finance internally in the notebook. Data was then augmented to store the data for the previous 60 days closing price of the stock.

## Prerequisite Installation

Python version 3.8 or above. 
The prerequisites and dependencies will be installed using the following pip install command:-

pip install -r resources.txt

