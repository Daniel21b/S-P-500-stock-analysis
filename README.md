Introduction

This project aims to forecast the S&P 500 stock prices using two different machine learning techniques: ARIMA (AutoRegressive Integrated Moving Average) and LSTM (Long Short-Term Memory). We analyze the performance of each model and compare their predictive capabilities.
Table of Contents

    Introduction
    Installation
    Data Description
    ARIMA Model
    LSTM Model
    Model Evaluation
    Visualization
    Conclusion
    References

Installation

Clone the repository and install the required dependencies using pip.

git clone https://github.com/dberhane21/sp500-forecasting.git
cd sp500-forecasting

pip install -r requirements.txt

Data Description

The dataset contains historical S&P 500 stock prices from 2006 to 2023. The data includes the following columns:

    Date: The date of the observation.
    Open: The opening price.
    High: The highest price.
    Low: The lowest price.
    Close: The closing price.
    Volume: The trading volume.
    Adj Close: The adjusted closing price.
