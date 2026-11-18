# Duka Sales and Agent Cleanup

**Author:** Buhle Pearl Nkosi · 1Million Devs Cohort · Week 3 Assignment

## Summary of both engagements
1. **Duka Electronics sales exploration** (`duka_sales_exploration.ipynb`): inspection, derived columns, manager questions, branch/channel analysis, a Premium-Online Nairobi/Mombasa export, and an Excel workbook (SUMIFS, XLOOKUP, pivot values) reconciled to pandas.
2. **Agent network data cleanup** (`agent_cleanup.ipynb`, `cleaning_pipeline.py`): audit, reusable cleaning function with a log, merge validation, county summary and a Data Quality Report. *(Pending: add after the agent generator is available.)*

## Duka Executive Summary
Duka Electronics recorded 1,000 orders worth KES 71,792,500 between 01 Jan 2026 and 29 Jun 2026.

Nairobi is the top branch with KES 26,106,100, 36.4% of revenue, versus Mombasa at 19.5%.

Laptops generate KES 41,535,000 (57.9% of revenue), the largest of the five products.

Online orders number 320 (32.0% of orders) with an average of KES 71,207, against KES 70,759 in-store.

Premium-priced products (Laptop and Tablet) account for 84.8% of revenue from 435 orders.

## Agent data before and after
Rows before cleaning: **TBD** · Rows after cleaning: **TBD**

## How to regenerate the data and run the notebooks
1. `pip install -r requirements.txt`
2. `python generate_data.py` (writes `duka_sales.csv`, `agents.csv`, `agent_transactions.csv`; raw CSVs are not committed)
3. Open `duka_sales_exploration.ipynb` and `agent_cleanup.ipynb` and select Run all.
