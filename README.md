# Binance BTCUSDT Trading Script

This Python script uses the Binance API and the `requests` library to trade BTCUSDT. It sets the API key and secret, and then sends a POST request to the Binance API to execute the trade. The response from the API, which contains information about the trade, is printed to the terminal.

## Requirements
- Python 3.6 or later
- `requests` library

## Usage
1. Install Python and the `requests` library if you haven't already.
2. Replace `YOUR_API_KEY` and `YOUR_API_SECRET` with your own Binance API key and secret in the script.
3. Save the script with a `.py` extension, such as `trade_btcusdt.py`.
4. Run the script with the following command: python trade_btcusdt.py
The response from the Binance API will be printed to the terminal.

## Note
This script does not use the Binance library. It uses the `requests` library to send a POST request to the Binance API directly to trade BTCUSDT. The Binance API provides a way for developers to access the Binance exchange and trade cryptocurrencies programmatically, without the need for a separate library.
