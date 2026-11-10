# 🛒 Vannilas Supermarket Sales & Inventory Analysis

An end-to-end Excel analytics project for a supermarket in Kakuma Town, Kenya: cleaning a messy 15,500-record dataset, analysing sales and inventory performance, and building an interactive dashboard with recommendations for management.

> **Tools:** Microsoft Excel (data cleaning, formulas, PivotTables, Slicers, dashboard design)

---

## 📌 Business Problem

Vannilas Supermarket sells groceries, beverages, household items, personal care products, electronics, stationery, baby products, and clothing. After three years of transactions, management wants to understand:

- Sales performance and revenue trends
- Customer purchasing patterns
- Inventory movement, slow sellers, and stock shortages
- How to improve profitability and reduce stock-outs

## 🎯 Objectives

1. Clean and standardise the raw sales and inventory data
2. Identify top and bottom performing products, categories, and departments
3. Analyse monthly trends and payment method usage
4. Detect slow-moving products and stock-out risks
5. Provide data-backed recommendations to management

## 📂 Dataset

| Item | Detail |
|---|---|
| Records | 15,500 (raw) |
| Time span | 3 years |
| Categories | Groceries, Beverages, Household Items, Personal Care, Electronics, Stationery, Baby Products, Clothing |

> Note: The dataset is synthetic and was created for training purposes.

## 🧹 Data Cleaning

The raw data was intentionally messy. I cleaned it manually in Excel on a copy of the raw tab, keeping the original untouched.

- [Removed X duplicate records]
- [Fixed inconsistent category / product name spellings]
- [Handled missing values in ___]
- [Standardised date formats and payment method labels]
- [Corrected data types and invalid quantities / prices]

## 📊 Dashboard

**KPI Cards:** Total Revenue · Total Transactions · Total Products Sold · Average Transaction Value · Gross Profit · Inventory Turnover Rate

**Visuals:**
- Revenue by Product Category
- Monthly Sales Trend
- Revenue by Payment Method
- Top 10 Best-Selling Products
- Lowest-Selling Products
- Revenue by Department
- Inventory Levels by Category
- Stock-Out Analysis
- Profit by Category
- Customer Purchase Trend

**Slicers:** Department · Category · Date/Month

![Dashboard Preview]<img width="1104" height="362" alt="Screenshot 2026-11-10 110346" src="https://github.com/user-attachments/assets/22afa103-80a3-4eb0-8679-e096969bc357" />

<img width="1138" height="390" alt="Screenshot 2026-11-10 110505" src="https://github.com/user-attachments/assets/00e94876-8db7-42b2-b0be-f472d0b8cd20" />


## 🔍 Key Insights

1. **Revenue:** Total revenue was [KES ___], with an average transaction value of [KES ___].
2. **Top categories:** [Category] generated the most revenue, while [Category] had the highest profit margin.
3. **Seasonality:** Sales peaked in [months], likely due to [reason].
4. **Payment methods:** [Method] was the most used, accounting for [__%] of revenue.
5. **Slow movers:** [Products] had the lowest sales and are tying up stock.
6. **Stock-outs:** [Products / categories] frequently ran out of stock.

## 💡 Recommendations

- Increase reorder levels for frequently out-of-stock products
- Run promotions or bundle offers to clear slow-moving items
- Stock up ahead of peak months identified in the trend analysis
- Focus marketing and shelf space on high-margin categories
- [Add your own based on findings]

## 📑 Workbook Tabs

| Tab | Purpose |
|---|---|
| `Project brief` | Business background, objectives, business questions, and dashboard requirements |
| `Vannilas_Sales` | Original messy dataset (15,500 records), left untouched |
| `Working sheet` | Cleaned and standardised copy used for all analysis |
| `Summary` | PivotTables and calculations behind the KPIs and charts |
| `Dashboard` | Interactive dashboard with KPI cards, charts, and slicers |

## 📁 Repository Structure

```
├── Vannilas_Supermarket_Sales_Inventory_Analysis.xlsx
├── images/
│   └── dashboard.png
└── README.md
```

## 🚀 How to Use

1. Download `Vannilas_Supermarket_Sales_Inventory_Analysis.xlsx`
2. Open it in Microsoft Excel (2016 or later)
3. Go to the **Dashboard** tab and use the slicers to filter by department, category, and date/month
4. Check `Vannilas_Sales` and `Working sheet` to see the before-and-after of the cleaning process

## 👤 Author

**Alek**
Data Analytics student | ARel Data Science Program
📍 Kakuma, Kenya
🔗 [LinkedIn](www.linkedin.com/in/monicah-majok) · 

