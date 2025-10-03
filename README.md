**About**:

Python utility for downloading historical candlestick (klines) data from Binance—useful for cryptocurrency analysis, trading strategies, or data science projects. Supports both Spot and Futures markets with flexible interval and time selection.

**Features**:

Fetches historical OHLCV (Open, High, Low, Close, Volume) data for any Binance symbol.
Can download Spot or Futures data.
Outputs the data as a clean pandas DataFrame.
Easily switch trading pairs, intervals, and time ranges.

**Requirements**:

Python 3.7+
binance library
pandas library


**Usage**:

Update your API key and secret inside the script, type a valid Binance symbol (e.g. "BTCUSDT", "ETHUSDT"):
*api_key = 'YOUR_API_KEY'
api_secret = 'YOUR_API_SECRET'*
Its to interract with the binance application, to get these keys follow ChatGPT Steps.


**Security Notice**:

Never commit actual API keys/secrets in your code or push them to public repositories.
Always use environment variables or secure config files for secrets in production.

**License**
MIT License. This script is for educational purposes only. Use at your own risk.

**Disclaimer**
Not financial advice. Cryptocurrency trading involves significant risk. API usage may be limited by account permissions or Binance API changes.
