# 🛒 SuparMart Sales Analysis — Tableau Dashboard

An end-to-end sales analytics project built on the **Sample Superstore** dataset, visualized using **Tableau**. The dashboard uncovers key business insights around sales performance, profitability, regional trends, customer segments, and shipping behaviour across four years (2019–2022).

---

## 📁 Repository Structure

```
├── Sample - Superstore-Main.xlsx   # Source dataset (Orders, Returns, People)
├── SuparMartSalesAnalysis.twb      # Tableau workbook (all dashboards & worksheets)
└── README.md
```

---

## 📊 Dataset Overview

**File:** `Sample - Superstore-Main.xlsx`

| Sheet | Description |
|---|---|
| `Orders` | 9,994 transaction records across the US (2019–2022) |
| `Unique Returns` | 296 returned orders with Order IDs |
| `People` | Regional managers mapped to their respective regions |

### Key Fields (Orders Sheet)

| Field | Type | Description |
|---|---|---|
| Order ID | String | Unique order identifier |
| Order Date / Ship Date | Date | Order placement and shipping dates |
| Ship Mode | String | Second Class, Standard Class, First Class, Same Day |
| Customer ID / Name | String | Customer identifiers |
| Segment | String | Consumer, Corporate, Home Office |
| Region / State / City | String | Geographic breakdown (4 regions, US-wide) |
| Category / Sub-Category | String | 3 categories, 17 sub-categories |
| Sales | Decimal | Revenue per line item |
| Quantity | Integer | Units sold |
| Discount | Decimal | Discount applied (0–1 scale) |
| Profit | Decimal | Profit per line item |

### Dataset Summary

| Metric | Value |
|---|---|
| Total Records | 9,994 rows |
| Date Range | Jan 2019 – Dec 2022 |
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Unique Orders | 5,009 |
| Unique Customers | 793 |
| Product Categories | Furniture, Office Supplies, Technology |

---

## 📈 Tableau Dashboards

**File:** `SuparMartSalesAnalysis.twb`

The workbook contains **3 dashboards** built from **11 worksheets**.

---

### Dashboard 1 — Sales Overview & Time Analysis

Provides a high-level view of sales performance over time.

**Worksheets included:**
- **Total Sales** — KPI card showing overall revenue
- **Total Profit** — KPI card showing overall profit
- **Total Orders** — KPI card showing order volume
- **Total Quantity Sold** — KPI card showing units sold
- **Sales Trend Over Time** — Line chart tracking revenue trajectory
- **Sales by Year-Month** — Monthly sales breakdown across all years

---

### Dashboard 2 — Region & Shipping Analysis

Explores geographic distribution and logistics patterns.

**Worksheets included:**
- **Sales by Region** — Regional revenue comparison
- **Sales and Profit by Region** — Side-by-side sales vs. profit by region
- **Relative % Sales and Profit by Region** — Proportional share analysis
- **Shipping Mode Analysis** — Distribution of orders by shipping method

---

### Dashboard 3 — Product & Profitability Analysis

Digs into product-level and segment-level performance.

**Worksheets included:**
- **Sales by Subcategory and Region** — Cross-dimensional product breakdown
- **Average Profit by Segment** — Profitability across Consumer, Corporate, and Home Office segments
- **Sales vs Profit Relationship** — Scatter plot exploring the discount–profit dynamic

---

## 🔧 How to Use

1. **Clone or download** this repository.
2. Open `SuparMartSalesAnalysis.twb` in **Tableau Desktop**.
3. When prompted, re-point the data source to `Sample - Superstore-Main.xlsx` from your local folder.
4. All dashboards and worksheets will load automatically.

> **Note:** The `.twb` file stores the workbook structure and references the Excel file as an external data source. Make sure both files are in the same directory, or update the data source path manually inside Tableau via *Data → Edit Data Source*.

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel (.xlsx) | Data storage and source |
| Tableau Desktop 2026.1 | Dashboard design and visualisation |
| GitHub | Version control and project sharing |

---

## 💡 Key Insights (Preview)

- **Technology** generates the highest sales but **Office Supplies** leads in profit margin.
- **West** and **East** regions consistently outperform Central and South.
- High **discounts** (>30%) strongly correlate with negative profit — a key business risk.
- **Standard Class** shipping accounts for the majority of orders, while **Same Day** is rarely used.
- The **Consumer** segment drives the highest order volume across all years.

---

## 👤 Author

**Tarang Agarwal**

---

## 📄 License

This project uses the publicly available **Sample Superstore** dataset provided by Tableau Software for educational and demonstration purposes.
