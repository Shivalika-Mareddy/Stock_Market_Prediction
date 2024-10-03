
# Stock Market Prediction Using Stacked LSTM with Dropout and Dense Layers

This project focuses on building a stock market prediction model using a stacked Long Short-Term Memory (LSTM) network with Dropout and Dense layers. The model is trained on historical stock price data to predict future stock prices. The LSTM network is well-suited for time-series data, making it an effective choice for predicting trends in stock prices.

## Features

- Stacked LSTM Layers: Leverages multiple LSTM layers to capture long-term dependencies in time-series data.
- Dropout: Prevents overfitting by randomly dropping units during training.
- Dense Layer: Provides the final output for the predicted stock price.


## Installation

Install the required dependencies:

```bash
  pip install tensorflow pandas numpy scikit-learn matplotlib
```
If you're using standalone Keras, you can install it with :
```bash
  pip install Keras
```
However, note that TensorFlow 2.x already includes the Keras API, so you typically do not need to install Keras separately when using TensorFlow 2.x.


## Usage

1.Make sure your stock market data CSV file is placed in the project directory. The CSV file should include historical stock prices with columns like Date, Open, High, Low, Close, and Volume.

2.Update the csv_path in the script with the path to your CSV file:
```bash
 csv_path="/path/to/your/stocks.csv"
```
3.Execute the script.

4.After running the script, the model will predict the stock prices for the next 30 days based on historical data.


## Contributions

Contributions are always welcome!



