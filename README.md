# 🦈 Shark Tank India — Sales & Investment Analysis Dashboard

A comprehensive data analytics project built on the **Shark Tank India** dataset (Seasons 1–5), visualized using **Tableau**. The dashboard explores pitch outcomes, investment trends, shark behaviour, industry performance, and founder demographics across all five seasons.

---

## 📁 Repository Structure

```
├── Shark_Tank_India.csv              # Source dataset (789 pitches, 80 columns)
├── SharkTankIndiaDashboard.twb       # Tableau workbook (3 dashboards, 18 worksheets)
└── README.md
```

---

## 📊 Dataset Overview

**File:** `Shark_Tank_India.csv`

| Attribute | Details |
|---|---|
| Total Rows | 789 pitches |
| Total Columns | 80 |
| Seasons Covered | Season 1 – Season 5 |
| Air Date Range | Dec 2021 – Mar 2026 |

### Column Categories

| Category | Fields |
|---|---|
| **Show Info** | Season Number, Episode Number, Pitch Number, Original Air Date, Episode Title, Anchor |
| **Startup Info** | Startup Name, Industry, Business Description, Company Website, Started in |
| **Financials** | Yearly Revenue, Monthly Sales, Gross Margin, Net Margin, EBITDA, Cash Burn |
| **Pitch Details** | Original Ask Amount, Original Offered Equity, Valuation Requested |
| **Deal Outcome** | Received Offer, Accepted Offer, Total Deal Amount, Total Deal Equity, Total Deal Debt, Deal Valuation |
| **Shark Details** | Individual investment amount, equity, and debt for each of the 7 sharks + guest sharks |
| **Founder Info** | Number of Presenters, Male/Female/Transgender Presenters, Pitchers Average Age, Pitchers City/State |
| **Shark Presence** | Boolean flags for which sharks were present per episode |

### Dataset Summary

| Metric | Value |
|---|---|
| Total Pitches | 789 |
| Pitches that Received an Offer | 502 |
| Offers Accepted | 434 |
| Total Investment (All Seasons) | ₹34,822.91 Lakhs |
| Average Deal Size | ₹80.24 Lakhs |
| Industries Represented | 18 |
| Top Industries | Food & Beverage, Beauty/Fashion, Tech/Software, Medical/Health, Lifestyle/Home |
| Top Pitcher States | Maharashtra, Delhi, Karnataka, Gujarat, Haryana |

### Shark-wise Investment Summary

| Shark | Total Invested | No. of Deals |
|---|---|---|
| Aman Gupta | ₹7,772.9 L | 164 |
| Namita Thapar | ₹5,427.7 L | 136 |
| Anupam Mittal | ₹4,662.8 L | 120 |
| Peyush Bansal | ₹4,072.9 L | 104 |
| Vineeta Singh | ₹3,420.6 L | 98 |
| Ritesh Agarwal | ₹2,690.2 L | 59 |
| Amit Jain | ₹1,384.4 L | 38 |

---

## 📈 Tableau Dashboards

**File:** `SharkTankIndiaDashboard.twb`

The workbook contains **3 dashboards** built from **18 worksheets**.

---

### Dashboard 1 — Shark Tank India Overview

A high-level snapshot of show performance and pitch outcomes.

**Worksheets included:**
- **Total Startups** — KPI card showing total pitches across all seasons
- **Total Deals** — KPI card showing total accepted deals
- **Total Investment** — KPI card showing cumulative investment
- **Deal Success Rate** — Overall percentage of pitches that converted to deals
- **Deals Accepted vs Rejected** — Comparative breakdown of pitch outcomes
- **Season-wise Pitches** — Volume of pitches across each season

---

### Dashboard 2 — Investment Analysis

Deep-dives into deal sizes, valuations, and investment patterns.

**Worksheets included:**
- **Avg Ask Amount** — Average amount requested by founders
- **Avg Deal Amount** — Average amount actually invested
- **Ask vs Deal Amount** — Gap analysis between ask and final deal
- **Season-wise Investment Trend** — How total investment evolved season over season
- **Number of Sharks vs Deal Amount** — Relationship between syndicate size and deal value
- **Revenue vs Deal Amount** — Correlation between startup revenue and investment received
- **Industry-wise Funding** — Which industries attracted the most capital
- **Industry Success Rate** — Conversion rate by industry

---

### Dashboard 3 — Founder & Geography Analysis

Explores who the founders are and where they come from.

**Worksheets included:**
- **Industry-wise Startups** — Distribution of pitches by industry
- **Average Revenue by Industry** — Revenue benchmarks across sectors
- **State-wise Startups** — Geographic heatmap of founder origins
- **Founder Age Distribution** — Age profile of pitchers
- **Total Startups (KPI)** — Supporting KPI for context

---

## 🔧 How to Use

1. **Clone or download** this repository.
2. Open `SharkTankIndiaDashboard.twb` in **Tableau Desktop**.
3. When prompted, re-point the data source to `Shark_Tank_India.csv` from your local folder.
4. All dashboards and worksheets will load automatically.

> **Note:** The `.twb` file references the CSV as an external data source. Make sure both files are in the same directory, or update the path via *Data → Edit Data Source* inside Tableau.

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|---|---|
| CSV (Excel-compatible) | Data storage and source |
| Tableau Desktop | Dashboard design and visualisation |
| GitHub | Version control and project sharing |

---

## 💡 Key Insights (Preview)

- Only **55% of pitches** that received an offer were ultimately accepted, showing founders' negotiating stance.
- **Aman Gupta** leads all sharks in both deal count (164) and total capital deployed.
- **Food & Beverage** is the most pitched industry, but **Technology/Software** attracts higher average deal sizes.
- **Maharashtra and Delhi** together account for the largest share of founders.
- Deal amounts rise significantly when **2 or more sharks** co-invest, suggesting collaborative deals are more lucrative.
- Investment volume has grown consistently from Season 1 to Season 5, reflecting the show's expanding scale.

---

## 👤 Author

**Tarang Agarwal**

---

## 📄 License

This project uses publicly available data sourced from Shark Tank India for educational and analytical purposes only.
