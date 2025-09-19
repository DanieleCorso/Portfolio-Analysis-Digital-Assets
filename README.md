# Portfolio-Analysis-Digital-Assets
A Python-based quantitative analysis of the impact of integrating digital assets (BTC, ETH) into a traditional 60/40 investment portfolio.

# Multi-Asset Portfolio Analysis: Integrating Digital Assets

### A quantitative analysis of the impact of including Bitcoin and Ethereum in a traditional 60/40 investment portfolio.

**Author:** Daniele [Cognome]
**Date:** [Mese, Anno]
**Jupyter Notebook:** [`portfolio_analysis.ipynb`](./portfolio_analysis.ipynb)  <!-- Assicurati che il nome del file sia corretto -->
**LinkedIn:** [linkedin.com/in/suo-profilo]


---

## 1. Project Objective

The rise of digital assets has presented a new frontier for investors. However, institutional adoption requires a rigorous, data-driven understanding of their impact on traditional portfolio structures. 

This project aims to answer a fundamental question for modern portfolio management: **What is the quantitative impact of allocating a small portion of a traditional 60/40 equity/bond portfolio to major cryptocurrencies like Bitcoin and Ethereum?**

Through this analysis, I demonstrate my ability to:
- Source and process financial data from multiple APIs.
- Conduct quantitative portfolio analysis using Python.
- Evaluate risk-adjusted returns and diversification benefits.
- Communicate complex financial insights through clear data visualization.

This project directly applies concepts from my studies in **Corporate Finance**, **Investment Principles**, and the **CAIA (Chartered Alternative Investment Analyst)** curriculum.


---

## 2. Methodology & Tools

This analysis was conducted in a Jupyter Notebook using Python and several key data science libraries.

*   **Programming Language:** Python 3.9
*   **Core Libraries:**
    *   `pandas` for data manipulation and analysis.
    *   `numpy` for numerical operations.
    *   `yfinance` for sourcing historical price data for traditional assets.
    *   `pycoingecko` for sourcing historical price data for digital assets.
    *   `matplotlib` & `seaborn` for data visualization.
*   **Analysis Period:** [e.g., January 1, 2018 - December 31, 2023] _(Questo è un buon periodo che include sia bull che bear market)_
*   **Assets Analyzed:**
    *   **Equities:** SPDR S&P 500 ETF (SPY)
    *   **Bonds:** iShares Core U.S. Aggregate Bond ETF (AGG)
    *   **Digital Assets:** Bitcoin (BTC) and Ethereum (ETH)

---

## 3. Key Findings & Analysis

The analysis compares three distinct portfolio allocations:

1.  **Traditional Portfolio:** 60% Equities (SPY), 40% Bonds (AGG)
2.  **Hybrid Portfolio (BTC):** 55% Equities, 35% Bonds, 10% Bitcoin (BTC)
3.  **Hybrid Portfolio (ETH):** 55% Equities, 35% Bonds, 10% Ethereum (ETH)

### Performance Summary

| Portfolio Metric            | Traditional (60/40) | Hybrid (BTC) | Hybrid (ETH) |
| --------------------------- | -------------------- | -------------- | -------------- |
| **Annualized Return**       | [e.g., 8.5%]         | [e.g., 15.2%]  | [e.g., 17.1%]  |
| **Annualized Volatility**   | [e.g., 12.1%]        | [e.g., 18.5%]  | [e.g., 22.3%]  |
| **Sharpe Ratio**            | [e.g., 0.65]         | [e.g., 0.78]   | [e.g., 0.74]   |
| **Max Drawdown**            | [e.g., -20.4%]       | [e.g., -35.8%] | [e.g., -45.2%] |

_(Note: These are placeholder values. Daniele dovrà sostituirli con i risultati reali della sua analisi.)_

### Key Visualizations

**1. Cumulative Portfolio Performance**
![Cumulative Performance Chart](images/cumulative_performance.png)  <!-- Immagine salvata in una cartella 'images' -->
*This chart clearly shows that while the hybrid portfolios exhibit higher volatility, their cumulative returns over the analysis period significantly outpaced the traditional 60/40 allocation.*

**2. Asset Correlation Matrix**
![Correlation Matrix](images/correlation_matrix.png) <!-- Immagine salvata in una cartella 'images' -->
*The correlation matrix highlights the low-to-moderate correlation between digital assets (BTC, ETH) and traditional assets (SPY, AGG), confirming their potential diversification benefits.*

---

## 4. Conclusion & Business Implications

The inclusion of a modest allocation to Bitcoin or Ethereum **materially improved the portfolio's overall return and its risk-adjusted performance (Sharpe Ratio)** over the selected period. 

However, this enhanced performance came at the cost of **significantly higher volatility and larger maximum drawdowns**, a critical consideration for any risk-averse investor. 

This analysis underscores the importance of a sophisticated approach to risk management when integrating digital assets. While they offer compelling diversification and return potential, their unique volatility profile must be actively managed. This project serves as a practical foundation for the more advanced risk modeling and due diligence required in institutional asset management.


---

## 5. How to Run This Project

To replicate this analysis, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [URL del suo repository GitHub]
    cd [nome-repository]
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy yfinance pycoingecko matplotlib seaborn jupyter
    ```
3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook portfolio_analysis.ipynb
    ```
