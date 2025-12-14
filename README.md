# Professional Backtesting Framework for Quantitative Trading

**Obsidian Financial Research** – [https://obsidianresearch.net/](https://obsidianresearch.net/)

## Overview

This project explores how to design and implement a **professional backtesting framework** for quantitative trading using Python. The goal is not to present a profitable trading system, but to demonstrate how **theoretical concepts from quantitative finance and statistics can be translated into a systematic, testable, and unbiased trading model applied to real market data**.

The framework emphasizes **methodological rigor**: data validation, bias avoidance, risk management, and statistical evaluation of results. A complete example strategy based on **high-impact macroeconomic news** is implemented to illustrate each step of the process, from raw data to performance analysis.

## Key Objectives

* Build a **fully systematic trading model** with no discretionary decisions
* Show how to correctly **structure a backtest** to avoid common biases
* Apply **statistical reasoning** to strategy evaluation
* Highlight the gap between in-sample performance and real-world robustness

## Strategy Summary

The example strategy is a **news-driven trend-following model** applied primarily to **EUR/USD**, later extended to other assets (XAU/USD, USD/JPY).

Core logic:

* Trades are triggered by **high-impact macroeconomic news**
* Entry depends on price breaking the high/low of the post-news candle
* Risk is managed through predefined **stop loss and take profit** rules
* Parameters such as risk-reward ratio and time window are systematically tested

## Framework Components

* Data collection and validation (price data + economic calendar)
* Signal generation and trade execution logic
* Debugging and bias detection (look-ahead, survivorship, overfitting)
* Performance metrics and statistical analysis
* Risk management and portfolio-level evaluation

## Methodological Focus

Particular attention is given to:

* Overfitting and parameter optimization
* Train / validation split and walk-forward analysis
* Hypothesis testing to assess statistical significance
* Monte Carlo simulations for position sizing

## Disclaimer

This project is **for educational and research purposes only**. The implemented strategy is not intended for live trading without further out-of-sample testing, transaction cost modeling, and real-time validation.

## Author

**Mirko Piazzalunga**
Obsidian Financial Research

