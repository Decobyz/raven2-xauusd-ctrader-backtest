# raven2-xauusd-ctrader-backtest
A cTrader XAUUSD H1 cBot backtest using historical tick data from Pepperstone, with performance reporting and strategy evaluation.
# raven2 — XAUUSD cTrader cBot Backtest

## Overview

This repository documents the historical backtesting results of **raven2**, a cTrader cBot tested on XAUUSD using the H1 timeframe.

The goal of this project is to evaluate the bot's historical performance and continue investigating its robustness across different market conditions.

## Backtest Configuration

| Parameter | Value |
|---|---|
| Trading platform | cTrader |
| cBot | raven2 |
| Instrument | XAUUSD (Gold) |
| Timeframe | H1 |
| Data source | Pepperstone |
| Backtest period | 1 January – 27 October 2026 |
| Starting capital | $5,000 |
| Data type | Historical tick data |

## Reported Results

| Metric | Result |
|---|---:|
| Net profit | $1,536.46 |
| Reported return | 30.73% |
| Ending balance/equity | $6,536.46 |

These figures represent the results reported by the historical backtest. They do not represent verified live trading performance.

## Project Files
<img width="755" height="443" alt="I" src="https://github.com/user-attachments/assets/93be752c-452b-4262-86f1-a4e56a5db161" />
<img width="737" height="422" alt="A" src="https://github.com/user-attachments/assets/40dfa0fa-6061-4965-a9d3-1de2790c33a7" />

<img width="752" height="346" alt="N" src="https://github.com/user-attachments/assets/ab793a7e-d3bd-434b-a911-568d45d6fdbb" />



## Ongoing Research

My focus is not only on profitability, but also on understanding how the strategy behaves across different market regimes.

Further evaluation should include:

- Testing on different historical periods.
- Out-of-sample performance.
- Maximum drawdown and risk-adjusted returns.
- Trade distribution and exposure.
- Sensitivity to trading costs and market conditions.

## Disclaimer

This project is shared for research, educational and development purposes only. Historical backtest results do not guarantee future performance. Trading leveraged financial instruments involves substantial risk.

## Author

Computer Science student interested in algorithmic trading, quantitative research and cTrader automation.
