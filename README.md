# E-Commerce Customer Satisfaction & Revenue Intelligence
**Capstone Project 2 | Data Analytics Program**

---

## Business Problem
> **"Which product categories and cities drive the highest revenue, and what factors most influence customer satisfaction ratings in Indian e-commerce?"**

Indian e-commerce platforms face two core challenges: maximising revenue per order and maintaining high customer satisfaction. This project analyses 10,000 transactions across 5 cities and 4 product categories to surface actionable insights for operations, marketing, and customer experience teams.

---

## Team
| Member | Role |
|--------|------|
| Anmol | ETL Pipeline & Data Cleaning |
| Tushar Kumar | EDA & Statistical Analysis |
| Saad Arqam | KPI Design & Dashboard Build |
| Harshvardhan Singh | Business Recommendations |
| Arun Kumar | Report Writing & Presentation |

---

## Dataset
- **Source:** Synthetic e-commerce transaction data (India)
- **Size:** 10,000 rows × 12 columns
- **Period:** January – March 2024
- **Sector:** Retail / E-Commerce

---

## Key KPIs
| KPI | Value |
|-----|-------|
| Total Revenue | ₹74.84 Cr |
| Avg Order Value | ₹74,839 |
| Avg Customer Rating | 3.01 / 5 |
| Avg Delivery Days | 5.0 days |

---

## Repository Structure
```
SectionA_Team01_EcommerceAnalytics/
├── README.md
├── data/
│   ├── raw/              ← Original dataset (never edited)
│   └── processed/        ← Cleaned output from pipeline
├── notebooks/
│   ├── 01_extraction.ipynb
│   ├── 02_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_statistical_analysis.ipynb
│   └── 05_final_load_prep.ipynb
├── scripts/
│   └── etl_pipeline.py
├── tableau/
│   ├── screenshots/
│   └── dashboard_links.md
├── reports/
│   ├── project_report.pdf
│   └── presentation.pdf
└── docs/
    └── data_dictionary.md
```

---

## Tools Used
- **Python + Jupyter** — ETL, EDA, Statistical Analysis
- **Tableau Public** — Interactive Dashboard
- **GitHub** — Version Control

---

## Key Findings
1. Furniture leads revenue at ₹19.2 Cr (25.7% share)
2. Pune generates the highest city revenue at ₹16.2 Cr
3. Payment methods are evenly split: Card/COD/UPI ~31.7% each
4. Delivery speed has minimal correlation with ratings (r = -0.007)
5. Rating distribution is nearly uniform across 1–5 stars

---

## Tableau Dashboard
See `tableau/dashboard_links.md` for the published URL.
