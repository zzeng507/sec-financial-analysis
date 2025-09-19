# SEC Financial Analysis

Comparative financial analysis of **Tesla (TSLA)**, **Nvidia (NVDA)**, and **Ford (F)** using SEC EDGAR filings and Python.

---

## Project Overview
This project demonstrates an end-to-end pipeline to extract, clean, and analyze financial data from the **SEC EDGAR API** and **Yahoo Finance**.  
It focuses on:
- Automating SEC data collection  
- Cleaning inconsistent financial keys  
- Calculating financial ratios (PE, PEG, EBITDA margin, Debt-to-Equity, etc.)  
- Comparing 3 companies with different industry contexts  

---

## Tech Stack
- **Python** (pandas, numpy, matplotlib, requests)  
- **Google Colab / Jupyter Notebook**  
- **SEC EDGAR API** (company facts endpoint)  
- **Yahoo Finance** (stock price data)  

---

## Key Features
- Automated SEC API integration with fallback logic  
- Revenue growth (CAGR) and profitability ratios  
- Valuation metrics (PE, PEG) with error handling  
- Comparison dashboards across Tesla, Nvidia, and Ford  
- Exportable CSV and PDF report  

---

## How to Run

1. Clone the repo

```bash
git clone https://github.com/zzeng507/sec-financial-analysis.git
cd sec-financial-analysis
```

## A detailed PDF report and the full Jupyter Notebook are included in the repository for further review.

## Key Findings & Results

- **Nvidia**: Strongest growth (~36% CAGR), highest profitability (~47% EBITDA margin), but expensive valuation (PEG ~267).  
- **Tesla**: Overvalued (PE ~939), growth data inconsistent due to SEC key issues.  
- **Ford**: Modest growth (~8% CAGR), low margin, and negative earnings in the latest year.  

### Revenue Growth (2019–2024)
![Revenue Trend](images/revenue_trend.png)

### Valuation Metrics (PE & PEG)
![Valuation Table](images/valuation_table.png)

