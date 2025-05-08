🎵 MUSQ ETF – Exploratory Performance Analysis

This repository contains all data, Python code, and outputs used in the case study:

Early Performance Evaluation of MUSQ Global Music Industry ETF versus SPDR S&P 500 High Dividend ETF: A Case Study in Risk-Adjusted Return Metrics

🎯 Purpose

The aim of this project is to illustrate how core performance indicators—such as the Sharpe ratio, Sortino ratio, tracking error, and CAPM alpha/beta—behave in practice when applied to a novel asset class ETF. Using daily price data, the analysis compares the MUSQ ETF, which targets the global music industry, with a high-dividend equity benchmark (SPDR SPYD). While the timeframe is intentionally limited, the goal is to show both the power and limits of quantitative fund evaluation when data are sparse, volatile, or unconventional.

> ⚠️ Disclaimer: This is an educational case study. It is not an investment recommendation nor a complete performance audit.

---

🛠 Tools Used

- Python 3.11
- `pandas`, `numpy` – data wrangling
- `matplotlib` – charting
- `scikit-learn`, `statsmodels` – regression analysis (CAPM)

---

📊 Method Summary

- **Monthly returns**: based on closing prices from Bloomberg
- **Risk-free rate**: 10-year Polish government bond yield (5.30% as of March 2025)
- **CAPM model**: estimated using excess returns 
- **Key metrics**: CAGR, Sharpe, Sortino, tracking error, alpha, beta, R²

---

💡 Reflections

This project helped me:
- understand how performance metrics behave with small data samples,
- learn the limitations of CAPM in real fund analysis,
- see how tracking error and alpha may diverge in short timeframes.

---

📬 Contact

Feel free to reach out via LinkedIn: Arina Reutskaya (https://linkedin.com/in/arina-reutskaya)
Or open an Issue in this repository.
