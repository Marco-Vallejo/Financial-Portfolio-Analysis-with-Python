# Financial Portfolio Analysis with Python 📈

## Overview
This project analyzes the behavior of financial assets using real market data. The objective is to evaluate **returns**, **volatility**, and **correlation**, and to understand how diversification impacts portfolio risk.

---

## 📁 Project Structure
The repository contains two main analyses:

### 1. Two-Asset Portfolio
*   **Assets:** Apple (AAPL) and Microsoft (MSFT).
*   **Objective:** Analyze correlation and demonstrate the limitations of diversification when assets belong to the same sector.

### 2. Multi-Asset Portfolio
*   **Assets:**
    *   **AAPL** (Technology)
    *   **MSFT** (Technology)
    *   **XOM** (Energy)
    *   **GLD** (Defensive asset)
    *   **SPY** (Market benchmark)
*   **Objective:** Evaluate how diversification across different sectors reduces total portfolio risk.

---

## ⚙️ Methodology
1.  **Data extraction:** Using the `yfinance` library.
2.  **Transformation:** Converting prices into daily returns.
3.  **Calculations:**
    *   Mean returns.
    *   Volatility (Standard Deviation).
    *   Correlation matrix.
4.  **Portfolio Construction:** Building an equally weighted portfolio.
5.  **Risk Analysis:** Evaluating the impact of asset combinations.

---

## 📊 Key Findings
*   **Sector Correlation:** Technology stocks (AAPL, MSFT) show high correlation, limiting diversification benefits.
*   **Defensive Assets:** Gold (GLD) exhibits very low correlation with other assets, acting as a key diversifier.
*   **Volatility Reduction:** A diversified portfolio significantly reduces volatility compared to individual assets.

> [!IMPORTANT]
> **Key Insight:** Diversification is not about increasing the number of assets, but about combining assets with **low correlation**.

---

## 🛠️ Tools Used
*   **Language:** Python
*   **Libraries:** NumPy, Pandas, yfinance

## 🚀 Future Improvements
*   [ ] Portfolio optimization (Mean-Variance).
*   [ ] Sharpe ratio calculation.
*   [ ] Monte Carlo simulations for price forecasting.

