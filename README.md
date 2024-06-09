# Bitcoin Price Prediction and Trading Signals
This project focuses on developing a Bitcoin price prediction model using an LSTM neural network and generating trading signals based on RSI and Bollinger Bands technical indicators. The model is trained on 3 years of historical 1-minute OHLC data and backtested against various trading strategies.
## Installation
To run this project locally, please ensure you have Python 3.x installed. Clone this repository.
## Usage
The main script for this project is located in the bitcoin_prediction_and_trading.ipynb Jupyter Notebook. Open the notebook and run the cells sequentially to reproduce the results.
## Data
The project utilizes 3 years of historical 1-minute OHLC Bitcoin price data. The data is stored in the data directory and is preprocessed within the notebook.
## Model
The Bitcoin price prediction model is built using an LSTM neural network. The architecture of the model and the training process are described in detail within the notebook.
## Trading Signals
Trading signals are generated based on RSI and Bollinger Bands technical indicators. The implementation of these indicators and the signal generation process can be found in the notebook.
## Backtesting
The project includes a backtesting framework to evaluate the performance of various trading strategies based on the generated signals. The backtesting results are presented within the notebook.
## Results
The LSTM model achieves a low test MAE loss of 0.2979 and detects no anomalies in the test data. The RSI and Bollinger Bands signals match 89.1% of the time, and the backtested trading strategies result in substantial returns.
