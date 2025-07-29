# Market Basket Analysis

This repository contains a Market Basket Analysis project using Python and Jupyter Notebook to identify product associations in grocery shopping data. The project uses the **Apriori algorithm** to find frequent itemsets and generate association rules. It includes visualizations and a business-focused analysis in an HTML report.

---

## Project Overview

The goal of this project is to transform raw transactional data into actionable insights for product bundling, cross-selling recommendations, store layout optimization, and data-driven promotional strategies. By applying association rule mining, we identify meaningful product combinations that appear frequently in customer baskets, helping retailers improve sales and the overall shopping experience.

---

## Key Metrics Used

To measure the strength and reliability of product combinations, the analysis uses:

- **Support:** How often a product combination appears in all transactions.
- **Confidence:** The likelihood that a customer buys one product if they have bought another.
- **Lift:** The strength of the relationship compared to random chance (values above 1 indicate a meaningful association).

---

## Files in This Repository

- `Basket Analysis - AA.html` — Final report with results and visualizations, ready to view in any browser.  
- `Basket Analysis - AA.ipynb` — Jupyter Notebook for running or modifying the analysis.  
- `Groceries_dataset.csv` — The dataset containing grocery transactions used for the analysis. This file should be in the same folder as the notebook to run the code without changes.

## ⚡ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/aamine93/market-basket-analysis.git
   cd market-basket-analysis
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Basket Analysis - AA.ipynb"
   ```
3. Ensure `Groceries_dataset.csv` is in the same folder as the notebook.
4. Run all cells to reproduce the analysis.