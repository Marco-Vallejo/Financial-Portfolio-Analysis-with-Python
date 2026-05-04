# 📊 Financial Portfolio Analysis with Python

## 📌 Overview

This project analyzes the behavior of a diversified portfolio composed of five assets: AAPL, MSFT, XOM, GLD, and SPY.

The objective is to evaluate **risk, return, and diversification effects** using Python, applying key concepts from modern portfolio theory.

---

## 🎯 Objectives

* Calculate daily returns and volatility of financial assets
* Analyze relationships between assets using correlation and covariance
* Build an equally weighted portfolio
* Evaluate portfolio risk using both empirical data and the Markowitz model
* Understand the impact of diversification

---

## 🛠️ Tools & Libraries

* Python
* NumPy
* pandas
* yfinance
* matplotlib

---

## 📊 Methodology

### 1. Data Collection

Historical price data was downloaded using `yfinance` for the period 2020–2026.

### 2. Data Processing

* Daily returns were calculated using percentage change
* Missing values were handled appropriately
* Clean dataset prepared for analysis

### 3. Risk & Return Analysis

* Mean daily returns were computed
* Volatility (standard deviation) was calculated for each asset
* Correlation matrix was used to analyze relationships

### 4. Portfolio Construction

An equally weighted portfolio was created:

```python
pesos = np.array([0.2, 0.2, 0.2, 0.2, 0.2])
```

### 5. Covariance Matrix

The covariance matrix was computed to capture how assets move together.

### 6. Portfolio Risk (Markowitz Model)

Portfolio volatility was calculated using:

σₚ = √(wᵀ Σ w)

This allows measuring total risk considering both individual volatility and asset interactions.

---

## 📈 Key Results

* The portfolio shows **lower volatility than most individual assets**, confirming diversification benefits
* Assets like **AAPL and MSFT** exhibit high covariance, indicating concentrated risk
* **GLD** shows low covariance with other assets, acting as a diversification component
* The volatility calculated using the **Markowitz model closely matches empirical volatility**, validating the theoretical approach

---

## 🧠 Key Insights

* Diversification reduces risk, but its effectiveness depends on asset correlation
* Low-correlation assets are essential for improving the risk profile
* Portfolio risk is not a simple sum of individual risks
* The covariance structure is the main driver of portfolio behavior

---

## ⚠️ Limitations

* The model relies on historical data, which may not reflect future market conditions
* Correlations between assets can change over time
* The model assumes stable relationships and does not account for extreme market events

---

## 🚀 Conclusion

This project demonstrates that portfolio risk emerges from the interaction between assets rather than their individual characteristics alone.

The Markowitz framework provides a solid foundation for understanding diversification, though it should be complemented with more robust approaches in real-world applications.

---

## 📂 Project Structure

```bash
Project_1_two_assets/
Project_2_five_assets/
README.md
```

---

## 👨‍💻 Author

Marco Vallejo
Aspiring Financial Data Analyst
