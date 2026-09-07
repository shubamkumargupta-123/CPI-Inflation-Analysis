# CPI-Inflation-Analysis
Uncovering a decade of inflation trends across sectors using Excel
# CPI Inflation Analysis — India | Uncovering a decade of inflation trends across sectors using Excel

![Tool](https://img.shields.io/badge/Tool-Excel-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Overview

India's Consumer Price Index (CPI) is the key metric used to track inflation and guide monetary policy. This project analyzes over a decade of CPI data across Rural, Urban, and Combined sectors to understand which categories drive inflation, how it has evolved year-over-year, and how external shocks like COVID-19 and oil price swings have shaped the numbers.

## 📊 Dataset

- **Source:** All India Consumer Price Index data, published by the Ministry of Statistics and Programme Implementation (MoSPI), Government of India
- **Size:** 27 sub-categories × 3 sectors (Rural, Urban, Rural+Urban) × 124 months, 372 rows
- **Period covered:** January 2013 – May 2023

## 🛠️ Tools & Techniques

- **Tool:** Excel
- **Key techniques:** Pivot Tables, VLOOKUP/INDEX-MATCH, conditional formatting, the `CORREL` function, interactive dashboards

## 🔍 Approach

1. Cleaned the raw MoSPI index data, handling missing values (e.g. `NA` entries in the Housing category for early years) and verifying consistency across sectors.
2. Built pivot tables to compute each broader category's (Food, Clothing, Housing, Health, etc.) contribution to the overall CPI basket.
3. Calculated Year-over-Year inflation trends for Rural, Urban, and Combined sectors from 2013 onward to identify the highest-inflation year.
4. Investigated month-on-month food inflation (Vegetables, Milk, Pulses, Fruits) and the impact of COVID-19's first lockdown (Mar 2020) on Food, Household, and Health inflation.
5. Used the `CORREL` function to quantify the relationship between Fuel & Light and Transport & Communication inflation as a proxy for oil price pass-through.
6. Consolidated all findings into an interactive dashboard with a summary recommendation.

## 💡 Key Insights

- **Food & Beverages contributed ~44% of the overall CPI basket** — the highest of any broader category, meaning food prices have an outsized effect on India's headline inflation number.
- **2014 was the peak Y-o-Y inflation year**, with Combined (Rural+Urban) CPI rising ~6.6% — higher than any other year in the 2013–2019 window.
- **Found a 0.67 correlation between Fuel & Light and Transport & Communication inflation**, confirming that oil price movements pass through meaningfully into transport costs.
- **Vegetables were the most volatile food category**, swinging from +9.5% month-on-month in April 2022 to −12.7% in December 2022 — far more volatile than Milk, Pulses, or Fruits over the same period.

## 📷 Dashboard Preview

![Dashboard Screenshot](images/dashboard-screenshot.png)

*Add a screenshot or short GIF of your dashboard/chart here — this is the single most important visual for recruiters skimming your repo.*

## 📁 Repository Structure

```
├── README.md
├── data/
│   └── All_India_Index_Upto_April23.csv   # original raw MoSPI CPI dataset
├── images/
│   └── dashboard-screenshot.png
└── Cpi.xlsx                                # full analysis: pivot tables, 5 business questions, and dashboard
```

## ▶️ How to Reproduce

**Excel:** Open `Cpi.xlsx` and navigate through the `Question 1`–`Question 5` sheets to see each analysis step, or jump straight to the `Recommendation` sheet for the summary. The original raw data is included in `data/All_India_Index_Upto_April23.csv` for reference and reproducibility — it matches the `Raw Data` sheet inside the workbook.

## 👤 Author

**Shubham Kumar Gupta**
Data Analyst | [LinkedIn](https://www.linkedin.com/in/shubham-kumar-gupta-a4551b191) | [GitHub](https://github.com/shubamkumargupta-123)
