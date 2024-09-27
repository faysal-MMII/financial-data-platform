# Financial Data Platform

This project is a trading application that integrates with Alpaca and Schwab for live trading, and yahoo finance for downloading historical data. The project also provides backtesting capabilities. THere is no need to install Complex database systems like Cassandra and Postgress, SQLite is perfect enough, simply ensure you have it installed in your library. Placeholders are in place of the alpaca keys in the `SQLite_Trial.py` file , simply replace them with yours.

## Setup

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Configure your Alpaca API keys in the `SQLite_Trial.py` file
4. Run the main script: `python trading_ui.py`

## Features

- Live trading with Alpaca
- Backtesting capabilities
- Multiple trading strategies
- User-friendly GUI
