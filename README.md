#  Quantium Data Analytics Virtual Internship


##  About This Project
This repository contains all deliverables from the **Quantium Data Analytics Virtual Job Simulation** hosted on [Forage](https://www.theforage.com/). The simulation mirrors real-world analytics workflows at Quantium — one of Australia's leading data science and analytics firms — spanning data wrangling, statistical experimentation, and executive storytelling.

##  Repository Structure

```
Quantium-data-analytics/
├── Task1_Data_Preparation_Customer_Analytics/
│ ├── quantium_task1.ipynb ← Customer analytics notebook
│ ├──Task_1_DashBoard.pdf ← Power BI dashboard export
│ └── summary.txt ← Task brief and findings
├── Task2_Experimenting_Uplift_Testing/
│ └── quantium_task2.ipynb ← Uplift testing notebook
├── Task3_Analytics_Commercial_Application/
│ └── quantium_task3.pdf ← Commercial insights notebook
├──Quantium_completion_certificate.pdf
├── requirements.txt
└── README.md
```
---

## Tasks Overview

### Task 1 — Data Preparation & Customer Analytics
- Merged transaction and customer behaviour datasets
- Cleaned product names, extracted pack sizes and brand names
- Removed outliers and imputed missing dates
- Identified top customer segments by sales contribution
- **Key finding:** Budget Older Families and Mainstream Young Singles/Couples are the highest value segments

#### Power BI Dashboard Pages
| Page | Contents |
|---|---|
| Customer Demographics | PREMIUM_CUSTOMER and LIFESTAGE distribution by year, total sales by year |
| Sales Analysis | TOT_SALES by lifestage, customer tier, quarter and month |
| Product Quantity | PROD_QTY by month, weekday, quarter, lifestage and customer tier |

### Task 2 — Experimenting & Uplift Testing
- Selected control stores using Pearson correlation and sales similarity scoring
- Measured sales uplift for 3 trial stores during trial period
- **Key finding:** All trial stores showed positive uplift (12% to 32%) confirming the new layout drives sales

### Task 3 — Analytics & Commercial Application
- Synthesised findings from Tasks 1 and 2
- Developed data-driven commercial recommendations
- Presented insights in a format suitable for the category manager

## Tools Used

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation and analysis |
| `numpy` | Numerical computations |
| `matplotlib` | Data visualisations |
| `seaborn` | Statistical charts 
| `scipy` | Statistical significance testing |
| `Power BI` | Interactive dashboard and business reporting |


## 🏅 Completion Certificate

Successfully completed all three tasks and earned the official **Quantium Data Analytics Job Simulation Certificate** from Forage.
