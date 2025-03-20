# Stock Trading Strategies Overview

This repository contains the implementation of two distinct stock trading strategies. The strategies utilize historical daily price and volume data to generate trading signals based on various computed financial metrics and machine learning predictions.

## Strategy 1: Predictive Signal with LSTM and Transformer

### Description

This strategy integrates several technical indicators to forecast future stock returns. The core components of the model include:

- **Moving Averages:** Computes 5-day and 10-day moving averages of the stock prices to capture short-term trends.
- **Volatility:** Measures the volatility of stock prices over a rolling 5-day window to gauge market uncertainty.
- **Return Prediction:** Uses all indicators to predict the next day's stock return.

The model combines these factors to derive trading signals, aiming to exploit patterns detected from historical data to make profitable trading decisions.


## Strategy 2: Market Dynamics Analysis Using Financial Metrics

### Description

This strategy focuses on analyzing market dynamics through various financial metrics derived from trading data. The approach calculates different factors to understand and analyze liquidity, trading activity, and market performance:

- **Category Returns:** Includes sector-specific returns and market capitalization-weighted returns.
- **Liquidity Measures:** Turnover ratio and Amihud’s illiquidity measure.
- **Crowding Measures:** Industry crowding factor based on turnover discrepancies within sectors.

These metrics are used to identify potential trading opportunities by assessing market conditions, liquidity, and investor behavior.

## Usage

To run the strategies, clone the repository, and ensure Python 3.x is installed. 
