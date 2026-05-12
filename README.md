# News Sentiment Analysis — Predicting Price Moves with Financial Headlines

## Project Overview
A rigorous analytical pipeline built for **Nova Financial Solutions** that quantifies 
the sentiment expressed in financial news headlines and measures its statistical 
relationship with stock price movements.

The analysis combines **Natural Language Processing (NLP)**, **technical indicator 
computation**, and **Pearson correlation** to explore whether news sentiment can 
serve as a predictive tool for stock market trends.

---

## Business Objective
Enhance Nova Financial Solutions' predictive analytics capabilities by:
- Quantifying tone and sentiment in 55,987 financial news headlines using VADER NLP
- Computing technical indicators (SMA, EMA, RSI, MACD) for 6 major stocks
- Measuring the statistical correlation between news sentiment and daily stock returns
- Delivering actionable investment strategy recommendations

---

## Dataset
- **News**: FNSPID — 55,987 articles across 6,204 stocks (April 2011 – June 2020)
- **Prices**: yfinance API — daily OHLCV data for AAPL, TSLA, AMZN, MSFT, GOOGL, META
- **Benchmark**: SPY (S&P 500 ETF) for market-wide correlation analysis

---

## Key Finding
> Pearson r = +0.0199 (p = 0.32) — very weak positive correlation between 
> daily news sentiment and SPY returns, consistent with the Efficient Market Hypothesis.
> Positive sentiment days produce higher average returns than negative sentiment days.



