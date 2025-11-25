# 📈 Quantitative Stock Market Analysis Portfolio

[![View Live Project](https://img.shields.io/badge/View-Live_Interactive_Project-blue?style=for-the-badge&logo=github)](https://rashad1019.github.io/Quantitative_Analysis/)

**A professional quantitative finance project analyzing Risk vs. Return for MSFT, GBTC, TSLA, and NVDA.**

---

## 📄 Project Overview

This project demonstrates proficiency in **quantitative finance** and **data science** by applying rigorous statistical techniques to historical stock data. Moving beyond subjective investing, this analysis uses mathematical models to evaluate four distinct equities over a one-year period (Nov 2024 – Nov 2025).

**The Goal:** To determine the optimal investment choice by balancing **Volatility (Risk)** against **Annualized Returns**.

### 🎯 Objectives
*   **Data Engineering:** Robust collection and cleaning of financial time-series data.
*   **Statistical Analysis:** Calculation of daily returns, standard deviation, and correlation matrices.
*   **Risk Assessment:** Evaluation of volatility and Sharpe Ratios to measure risk-adjusted performance.
*   **Visualization:** Creation of interactive, professional charts using Plotly.

---

## 📊 Key Findings & Recommendation

After a comprehensive analysis of Volatility, Correlation, and Risk-Adjusted Returns:

### 🏆 **Final Recommendation: Microsoft (MSFT)**

*   **Why?** MSFT achieved the highest **Sharpe Ratio (0.801)**, indicating it delivered the best returns relative to the risk taken.
*   **Risk Profile:** It demonstrated the lowest annualized volatility (24.23%), making it the most stable asset in the portfolio.
*   **Performance:** Delivered a strong +22.38% total return without the extreme drawdowns seen in other tickers.

| Ticker | Total Return | Annualized Volatility | Sharpe Ratio | Verdict |
| :--- | :--- | :--- | :--- | :--- |
| **MSFT** | **+22.38%** | **24.23%** | **0.801** | ✅ **Strong Buy** |
| **NVDA** | +26.97% | 49.90% | 0.656 | ⚠️ High Volatility |
| **TSLA** | +18.18% | 65.55% | 0.523 | ❌ Excessive Risk |
| **GBTC** | -2.36% | 43.19% | 0.067 | ❌ Underperform |

---

## 🛠️ Methodology

The analysis follows a strict six-step quantitative workflow:

1.  **Data Collection:** Automated retrieval of daily OHLCV data via `yfinance`.
2.  **Descriptive Statistics:** Analysis of central tendency and dispersion.
3.  **Time Series Analysis:** Visualization of price trends and volume.
4.  **Volatility Analysis:** Calculation of 30-day rolling volatility to identify risk periods.
5.  **Correlation Analysis:** Heatmap visualization to understand diversification benefits.
6.  **Risk-Return Optimization:** Scatter plot analysis and Sharpe Ratio calculation.

---

## 💻 Technical Architecture

*   **Language:** Python 3.10+
*   **Environment:** Jupyter Notebook
*   **Libraries:**
    *   `pandas`: Data manipulation and time-series pivoting.
    *   `yfinance`: Reliable financial data API.
    *   `plotly`: Interactive, publication-quality visualizations.
    *   `numpy`: High-performance mathematical computing.

---

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Rashad1019/Quantitative_Analysis.git
    cd Quantitative_Analysis
    ```

2.  **Install dependencies:**
    ```bash
    pip install pandas yfinance plotly numpy
    ```

3.  **Run the Notebook:**
    ```bash
    jupyter notebook quantitative_stock_analysis.ipynb
    ```

---

## 👤 Contact

**Author:** Rashad Ferguson

📧 **Email:** [Rashad19@outlook.com](mailto:Rashad19@outlook.com)
🌐 **GitHub:** [github.com/Rashad1019](https://github.com/Rashad1019)
