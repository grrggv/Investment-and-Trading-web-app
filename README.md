# Stock Price Indicator

This is a python script for predicting stock price using data from _Quandl_.

## Important

- Authentication: Replace `quandl.ApiConfig.api_key = 'YOURAPIKEY'` to your own Quandl API Key.
- Libraries: Must have `quandl`, `parse`, `numpy`, `pandas`, and `matplotlib` installed to your python interpreter.

## Installation

1. Download and unzip this package. 
2. Replace authentication to your own Quandl API Key.
3. Install `quandl`, `parse`, `numpy`, `pandas`, and `matplotlib` to your python. You can use `pip install [library]` to install.

## How to use this script
1. Put in all the variables in *input.txt*.
2. Run `python main.py` in this directory.

## Formatting for input.txt
- Ticker symbols: Put down all your ticker symbols and separate each of them with `,`
- Start_date: Put down data training starting date with yyyy-mm-dd format or default(all the data from 2013 to 2016)
- End_date: Put down data traing ending date with yyyy-mm-dd format or default(all the data from 2013 to 2016)
- Predict_date: Put down the date you want to predict with yyyy-mm-dd format or default(predict stock prices for the recent week)
