# energy-stock-time-series-analysis

## Overview:
Using data from Yahoo Finance, I created price prediction charts of three individual stocks (EOSE, FLNC, NUAI) from 2022 into 2027. 

## Tools Used
- Python (pandas, matplotlib, seaborn, Prophet, yfinance)

## Dataset
- Yahoo Finance Public stock data

## Key Findings:
1. Of the 3 stocks, EOSE came up as the most volatile stock, with a standard deviation of 7.6%. FLNC came up as the least volatile, with a standard deviation of 6.2%
2. The Prophet tool predicts that NUAI will continue to recover towards $9-$10 by early 2027.
3. The Prophet tool seemed to highly underestimate a spike in 2025-2026, which is likely driven by a catalyst Prophet couldn't anticipate. The model predicts that EOSE will be valued at around $10 by 2027.
4. FLNC is the most forecastable of the three stocks because of its cyclical price behavior. The model predicts a strong recovery towards $35-$40 by 2027, nearing the company's original IPO prices.

## What I Learned:
In this practice project, I learned how to use the yfinance tool to extract stock data directly from Yahoo Finance. I learned how to use the Prophet tool to create charts that can display future price estimates for individual stocks. I also learned how to calculate and interpret 7-day and 30-day moving averages to identify bullish and bearish trend signals, and how to measure stock volatility using standard deviation of daily returns.
