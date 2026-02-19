# Statistical-Arbitrage-Pairs-Trading
Algorithmic trading project: Market Neutral Pairs Trading strategy using Engle-Granger cointegration on the Dow Jones and CAC 40.

# Algorithmic Trading: Statistical Arbitrage & Pairs Trading

**Author:** Cousquer Maxime
**Tech Stack:** Python, Pandas, Statsmodels, Seaborn, yfinance

## 🎯 Executive Summary
Development of a **Market Neutral** strategy based on Pairs Trading (Mean Reversion) applied to the Dow Jones (US) and CAC 40 (France). Unlike simple correlation, this project utilizes the **Engle-Granger Two-Step approach** to identify stationary spreads.

## 🚀 Key Achievements
* **Market Scanning:** Automated testing of over 1,000 pairs to map market efficiency.
* **Data Cleaning:** Identified and filtered out "spurious correlations" and data artifacts (e.g., illiquid assets or API errors).
* **Pair Selection:** Selected **Chevron (CVX) vs Exxon Mobil (XOM)** to optimize capital allocation (faster Half-Life mean reversion).
* **Risk Management:** Backtest achieved a **94% Hit Rate**, proving robustness to standard volatility, while highlighting vulnerabilities during extreme structural breaks (e.g., the COVID-19 crash).

## 📂 Files inside this repository
* `Statistical_arbitrage_pairs.ipynb`: The main Jupyter Notebook containing the code, formulas, and analysis.
* `Projet_Pairs_Trading.pdf`: A clean PDF export of the notebook for quick reading.
