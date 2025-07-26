# 📘 Limit Order Book Impact Modeling

This repository presents a comprehensive analysis of temporary market impact using Level-2 (MBP-10) limit order book data for three U.S. stocks: CRWV, FROG, and SOUN. We simulate order book dynamics, estimate the market impact of hypothetical orders, and model the cost curve using power-law functions.

---

## 🧠 Project Goals

- Reconstruct the limit order book from MBP-10 raw event data (top 10 levels).
- Simulate execution of various buy orders (100 to 5000 shares).
- Compute temporary price impact from these simulations.
- Fit a power-law model to estimate the relationship between order size and market impact.
- Answer two theoretical questions regarding impact modeling and execution strategy.

---

## 📂 Repository Structure

| File / Folder              | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `LOBImpactModel.ipynb`     | Main Jupyter Notebook — complete implementation of LOB reconstruction, market simulation, and model fitting for all three tickers. |
| `LOBImpact_Solutions.pdf`  | PDF report containing detailed answers to Question 1 & Question 2 based on the analysis. |
| `data/` (optional)         | Folder where the ZIP files (CRWV.zip, FROG.zip, SOUN.zip) should be placed, provided in the link : https://drive.google.com/drive/folders/1llpJkFnQSl2nauh9KsQ6alHOsOmXBog0|

---
