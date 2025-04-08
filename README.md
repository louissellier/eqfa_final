<p align="center">
  <img src="/data/cbs_logo.png" alt="Columbia Business School"/>
</p>

# 📊 Accounting Integrity as Alpha: Testing the Beneish M-Score in Portfolio Strategy

**Author**: Louis Sellier

**Course**: Earnings Quality and Fundamental Analysis (EQFA)  
**Institution**: Columbia Business School  
**Date**: Spring 2025

---

## 🧠 Overview

This project investigates whether forensic accounting insights—specifically the **Beneish M-Score**—can be used not only to detect potential earnings manipulation, but also to construct equity portfolios that outperform the market.

Using financial statement data from the **CFA Institute Level II curriculum dataset** and return data from **Alpha Vantage**, we:

- Compute M-Scores for a representative sample of U.S. firms (2001–2022)
- Run firm-level regressions to test whether M-Scores explain returns beyond market beta
- Build equally weighted portfolios based on M-Score rankings and compare them to the S&P 500

---

## 🧮 Methodology Summary

- **Model**: Beneish M-Score  
- **Sample Firms**: Apple, UnitedHealth, NVIDIA, ExxonMobil, General Electric, Costco, Johnson Controls, Intercontinental Exchange  
- **Data Period**:  
  - Financials: Quarterly from **2001–2022**  
  - Returns: Annual from **2010–2022**  
- **Data Sources**:  
  - CFA Institute Training Dataset  
  - Alpha Vantage API (price data)  
- **Analysis**:  
  - Annual rebalancing of Best/Worst M-Score portfolios  
  - Return comparison against SPY  
  - HC1-robust firm-level regressions
