# Kraken Crypto Tracker

This is a Python script that uses the Kraken Exchange API to track the price of selected cryptocurrencies in real time. It provides a visual interface using Streamlit and Plotly to interactively select a cryptocurrency and time interval, and displays a candlestick price chart and Relative Strength Index (RSI) chart.

## Installation

Before you can run this script, you need to install the required Python libraries. Use pip to install the required libraries:

`pip install krakenex pykrakenapi pandas streamlit plotly`

## Usage

To run this script, use the following command:

`streamlit run CriptDash.py`

In the side bar, you can select a cryptocurrency and a time interval. The script will then download the corresponding price data from Kraken and display the price and RSI charts.
## Features
- Connection to the Kraken API to fetch real-time cryptocurrency data.
- Interactive selection of cryptocurrency and time interval.
- Display of a candlestick price chart.
- Calculation and display of the 14-period Relative Strength Index (RSI).
- Calculation and display of a simple moving average (SMA) over a 14-period window.
## Error Handling
The script includes error handling for the API connection and data retrieval. If an error occurs during these processes, a message will be displayed on the user interface.
