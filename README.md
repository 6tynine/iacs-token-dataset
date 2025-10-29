# Simulated $IACS Token Market Data Dataset

## Short Description
This dataset provides simulated daily market data for the $IACS token (Omniacs.DAO) from January 1, 2025, to October 29, 2025. It includes price fluctuations based on a realistic random walk model with 5% volatility, trading volumes, and sentiment scores derived from hypothetical social media analysis. The data is fully synthetic and cleaned for immediate use in machine learning models, trading simulations, or volatility studies. Total: 302 entries in CSV format.

Columns:
- **Date**: YYYY-MM-DD format.
- **Price_USD**: Closing price in USD (rounded to 6 decimals).
- **Volume**: Simulated daily trading volume (integer).
- **Sentiment_Score**: Aggregated sentiment from -1.0 (bearish) to 1.0 (bullish).

Example usage: Load in Python with `pd.read_csv('iacs_simulated_data.csv')` and plot price trends with Matplotlib.

## Dataset Usage Guide
- **Cleaning Notes**: No missing values; data is sorted chronologically and validated for positive prices/volumes.
- **Applications**: Ideal for time-series forecasting (e.g., ARIMA), correlation analysis between sentiment and price, or backtesting DeFi strategies.
- **License**: MIT License – free for commercial/non-commercial use.

## My Pond Profile
Check out my profile on Pond for more bounties and contributions: https://cryptopond.xyz/developer/3e9af203-d945-4a15-a50c-3797524eae28

## Support $IACS
Join the Omniacs.DAO revolution! Stake $IACS today for governance power and yields. Buy on Uniswap (Base): https://dexscreener.com/base/0xd4d742cc8f54083f914a37e6b0c7b68c6005a024 🚀 #IACS #CryptoDAO
