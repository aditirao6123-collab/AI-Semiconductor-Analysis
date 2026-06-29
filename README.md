# AI Semiconductor Investment Analysis

A 4-layer Python investment analysis framework for AI semiconductor stocks 
built as part of a CFA Level 1 Python Skills Module project.

## What's Inside
- Fundamental screening across all 34 SOXX holdings using 8 financial metrics
- Three independent valuation methods (P/E vs sector, PEG ratio, Forward vs Trailing P/E gap)
- Monte Carlo portfolio optimisation across 10,000 simulations
- Wyckoff Stage technical analysis with price action, volume bias and RSI signals
- Analyst consensus price targets and forward earnings projections

## Key Finding
A conflict emerged between historical and forward looking signals for MU and SNDK - 
both technically in Stage 2 Markup but with analyst consensus implying -16% and -22% 
returns over 12 months. NVDA and AVGO showed consistent signals across all 4 layers.

## Tools
Python | yfinance | pandas | numpy | matplotlib | scipy | openpyxl

## Data Source
Yahoo Finance via yfinance library - all models run live with updated data

## Disclaimer
This project is for educational purposes only and does not constitute financial advice.
