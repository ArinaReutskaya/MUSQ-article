MGRN FIZ – Early Performance Evaluation

This repository contains all data, Python code, and outputs used in the case study:

**Early Performance Snapshot of Mount Globalnego Rynku Nieruchomości FIZ (MGRN FIZ) versus the S&P Global REIT Index: A Case Study in Risk-Adjusted Returns Metrics**

🎯 Purpose

The goal of this project is to demonstrate how key performance indicators—such as **Sharpe ratio**, **Sortino ratio**, **tracking error**, and **CAPM alpha/beta**—can be applied in a real-world fund evaluation context. The analysis is based on six months of data from MGRN FIZ, the first REIT-like investment fund listed on the Warsaw Stock Exchange.

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
