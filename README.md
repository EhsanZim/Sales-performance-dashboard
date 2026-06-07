# 📊 Sales Performance Dashboard — Advanced Excel Analytics Workbook

> A production-ready Excel dashboard for tracking sales KPIs, quota attainment, pipeline metrics, and regional performance. Built for Business Analysts, Sales Operations professionals, and anyone who needs a plug-and-play reporting solution — **no macros, no add-ins, no coding required.**

---

## 👤 Author

**Ehsan Zim**
🔗 [linkedin.com/in/ehsan-zim](https://www.linkedin.com/in/ehsan-zim) | 🐙 [github.com/EhsanZim](https://github.com/EhsanZim)

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Sales_Performance_Dashboard.xlsx` | Main workbook — fully functional with sample data |
| `README.md` | This documentation file |
| `CHANGELOG.md` | Version history and update log |

---

## 🗂️ Workbook Structure

The workbook contains **7 color-coded sheets**, each serving a distinct analytical purpose:

| Sheet | Tab Color | Purpose |
|-------|-----------|---------|
| 📋 **Executive Dashboard** | Navy | Top-level KPI summary view for leadership reporting |
| 🗄️ **Raw Data** | Gray | Master data table — all other sheets pull from here |
| 📈 **Monthly Trend** | Blue | Month-by-month revenue, targets, and MoM growth |
| 🗺️ **Regional Analysis** | Teal | Revenue and quota attainment broken down by region |
| 👤 **Rep Performance** | Purple | Individual sales rep scorecards with auto-tiering |
| 🔄 **Pipeline** | Amber | Deal stage funnel with weighted forecast values |
| 📖 **Instructions** | Green | Guide to using and customizing the workbook |

---

## ✨ Features

### Executive Dashboard
- Live KPI cards: **Total Revenue**, **Quota Attainment %**, **Deals Closed**, and **Average Deal Size**
- All KPI values auto-populate from sub-sheets — no manual updates needed
- Placeholder zones for embedding charts from analysis sheets

### Raw Data Sheet
- 96 rows of realistic randomized sample data across 12 months and 8 sales reps
- 15 tracked fields: Rep ID, Region, Month, Quarter, Product, Deal Stage, Revenue, Target, Units, Quota Attainment, Deals Closed, Avg Deal Size, Lead Source, Customer Type
- Auto-filter and freeze panes enabled for easy slicing
- All downstream sheets recalculate automatically when data is updated here

### Monthly Trend Analysis
- Month-by-month revenue vs. target comparison
- Auto-calculated **MoM Revenue Growth %**
- **Conditional formatting** traffic lights on Quota Attainment:
  - 🟢 Green — At or above target (≥ 100%)
  - 🟡 Amber — Near target (80–99%)
  - 🔴 Red — Below threshold (< 80%)
- Embedded clustered bar chart: Revenue vs. Target by month

### Regional Analysis
- Revenue, quota attainment, deal count, and share of total by region
- Auto-ranking formula (no manual sorting needed)
- Conditional formatting on attainment rate

### Rep Performance Scorecard
- Full-year aggregated metrics per sales rep
- **Performance Tier** auto-assigned by formula:
  - `Elite` — Quota ≥ 100%
  - `High Performer` — Quota ≥ 90%
  - `On Track` — Quota ≥ 75%
  - `Needs Attention` — Quota < 75%
- Color-coded quota attainment column

### Pipeline Funnel
- Six deal stages tracked: Prospecting → Qualified → Proposal → Negotiation → Closed Won → Closed Lost
- **Weighted Pipeline Value** = Total Value × Conversion Rate probability
- Color scale on weighted value column (red → yellow → green)

---

## 🚀 How to Use

### 1. Replace Sample Data
Navigate to the **Raw Data** sheet and replace the sample rows with your actual data. Keep the column headers exactly as-is — all formulas reference them by position.

### 2. Everything Else Updates Automatically
All five analysis sheets use formulas that read directly from Raw Data. Once you paste your data, every KPI, chart, and conditional format recalculates instantly.

### 3. Customize for Your Team
- Rename regions, rep names, products, and deal stages in the Raw Data sheet
- Adjust conversion rates in the **Pipeline** sheet (Column F) to match your actual close rates
- Extend the monthly rows if your fiscal year differs from Jan–Dec

---

## 📐 Technical Specifications

| Attribute | Detail |
|-----------|--------|
| **Format** | `.xlsx` — compatible with Excel 2016+ and Google Sheets |
| **Macros** | None — 100% formula-based |
| **Add-ins required** | None |
| **Formula count** | 312 dynamic formulas |
| **Formula errors** | Zero (verified) |
| **Conditional formatting rules** | 8 rules across 4 sheets |
| **Charts** | 1 embedded chart (Monthly Trend) |
| **Sample data rows** | 96 rows across 12 months × 8 reps |
| **Font** | Arial throughout |

---

## 🧰 Excel Techniques Used

- `SUMIF` / `AVERAGEIF` aggregation patterns
- `RANK()` for dynamic regional sorting
- `IF()` nested logic for performance tier classification
- Quota attainment: `=Actual/Target` with `0.0%` formatting
- MoM growth: `=(Current - Prior) / Prior`
- Weighted pipeline: `=Total Value × Conversion Rate`
- Conditional formatting with `CellIs` rules (≥, between, <)
- Color scale rule on pipeline values
- Auto-filter + freeze panes on Raw Data
- Cross-sheet formula references (e.g., `='Monthly Trend'!B14`)
- Clustered bar chart with dual series (Revenue vs. Target)

---

## 📊 Sample KPIs Tracked

| Metric | Formula Logic |
|--------|---------------|
| Total Revenue | `SUM` of all monthly revenue |
| Quota Attainment % | `Actual Revenue / Target Revenue` |
| MoM Growth % | `(Current Month − Prior Month) / Prior Month` |
| Avg Deal Size | `Total Revenue / Deals Closed` |
| Weighted Pipeline | `Deal Value × Stage Conversion Rate` |
| Regional Share | `Region Revenue / Grand Total Revenue` |
| Performance Tier | Nested `IF` on Quota Attainment % |
| YTD Rank | `RANK()` function on revenue column |

---

## 🔄 Compatibility

| Platform | Status |
|----------|--------|
| Microsoft Excel 2016+ | ✅ Full functionality |
| Microsoft Excel 365 | ✅ Full functionality |
| Google Sheets | ✅ Compatible (charts may need re-insertion) |
| LibreOffice Calc | ⚠️ Mostly compatible (minor formatting differences) |

---

## 📌 Use Cases

This dashboard is designed to be **industry-agnostic** and works equally well for:
- SaaS and software sales teams
- Retail and consumer goods organizations
- Financial services and insurance
- Consulting and professional services
- Any team tracking quotas, pipelines, and regional performance

---

## 📜 License

This project is released under the [MIT License](LICENSE). Free to use, adapt, and distribute for personal and commercial purposes. Attribution appreciated but not required.

---

*Built with Microsoft Excel and openpyxl. Questions or suggestions? Open an issue or connect on [LinkedIn](https://www.linkedin.com/in/ehsan-zim).*
