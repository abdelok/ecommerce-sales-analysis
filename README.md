# E-Commerce Sales Analysis

## Overview
Analysis of 240 transactions across product categories, regions, and time periods to identify revenue drivers and business opportunities.

**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Dataset:** Online Sales Dataset (Kaggle)

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Revenue | $80,568 |
| Average Order Value | $335.70 |
| Best Category | Electronics |
| Peak Month | January |
| Top Region | North America |

---

## Business Insights

**1. Electronics dominates revenue**  
Electronics is the highest-grossing category. Prioritizing stock and promotions in this segment can directly impact overall revenue.

**2. January is the peak month**  
Revenue peaks in January — likely driven by post-holiday sales or New Year demand. Inventory and marketing budgets should be increased before this period.

**3. North America leads all regions**  
North America generates the highest share of revenue. Targeted campaigns in this region offer the highest ROI.

---

## Recommendations

1. **Increase Electronics inventory before January** to capitalize on peak demand
2. **Double down on North America marketing** — highest revenue potential
3. **Run promotions in low-performing months** to smooth out revenue seasonality

---

## Visualizations

### Revenue by Category & Monthly Trend
![Revenue Analysis](outputs/revenue_analysis.png)

### Top 10 Products & Revenue by Region
![Products & Regions](outputs/products_regions.png)

---

## Project Structure

```
ecommerce-analysis/
├── data/
│   └── sales_data.csv
├── notebooks/
│   └── analysis.ipynb
├── outputs/
│   ├── revenue_analysis.png
│   └── products_regions.png
└── README.md
```

---

## How to Run

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook
```

Open `notebooks/analysis.ipynb` and run all cells.
