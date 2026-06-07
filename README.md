# 📊 Sales Performance Intelligence Dashboard — Advanced Excel Analytics

> An enterprise-grade Excel analytics workbook for Sales Operations, Revenue Operations, and Business Intelligence professionals. 500 deals, 12 reps, 8 products, 5 regions, 10 industries — across 12 color-coded sheets covering Win/Loss Analysis, Deal Velocity, Cohort Analysis, Pipeline Forecasting, and more. No macros. No add-ins.

---

## 👤 Author

**Ehsan Zim**
🔗 [linkedin.com/in/ehsan-zim](https://www.linkedin.com/in/ehsan-zim) &nbsp;|&nbsp; 🐙 [github.com/EhsanZim](https://github.com/EhsanZim)

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Sales_Performance_Dashboard_Advanced.xlsx` | Main workbook — 500 deals, 12 sheets, advanced analytics |
| `README.md` | This documentation file |
| `CHANGELOG.md` | Version history |

---

## 🗂️ Workbook Structure — 12 Sheets

| # | Sheet | Tab Color | Purpose |
|---|-------|-----------|---------|
| 1 | 📋 **Executive Dashboard** | Navy | 8×2 KPI grid + 8 chart zones for C-level reporting |
| 2 | 🗄️ **Deal Data** | Gray | 500-row master deal table, 29 fields |
| 3 | 📈 **Monthly Trend** | Dark Blue | Revenue, Win Rate, Margin, MoM Growth with embedded charts |
| 4 | 🏆 **Rep Scorecard** | Mid Blue | Individual rep KPIs with 5-tier performance classification |
| 5 | 🎯 **Win-Loss Analysis** | Dark Red | Win/Loss reasons, avg deal size, win rate by segment × region matrix |
| 6 | ⚡ **Deal Velocity** | Teal | Sales cycle analysis across 4 dimensions with bottleneck detection |
| 7 | 🔬 **Cohort Analysis** | Purple | Monthly + quarterly deal cohorts, New Logo vs Expansion split |
| 8 | 🔄 **Pipeline & Forecast** | Amber | Stage funnel, forecast categories, 3-scenario revenue model |
| 9 | 📦 **Product Analysis** | Dark Teal | 8 products: margin, win rate, cross-sell rate, revenue rank |
| 10 | 🌍 **Regional Analysis** | Steel | 5 regions: quota attainment, pipeline, margin, rank |
| 11 | 🔍 **Lead Source & Industry** | Gold | Source quality scoring, industry revenue and win rate breakdown |
| 12 | 📖 **Instructions** | Green | Full workbook guide |

---

## ✨ Feature Highlights

### Executive Dashboard
- **Row 1 KPIs:** Total ARR · Quota Attainment % · Weighted Pipeline · Win Rate · Deals Won
- **Row 2 KPIs:** Total Revenue · Avg Deal Size · Avg Sales Cycle (days) · Gross Margin % · Deals Lost
- 8 chart placeholder zones — paste from sub-sheets for a complete intelligence view

### Deal Data (Master Table — 500 rows, 29 fields)
Deal ID, Sales Rep, Region, Segment, Month, Quarter, Product, Category, Industry, Stage, Units, List Price, Discount %, Revenue, Target, Margin %, Gross Margin $, Days Open, Close Probability, Won, Lost, Win/Loss Reason, Lead Source, Customer Type, Forecast Category, ACV, ARR, CSAT, NPS

### Monthly Trend
- 15 tracked metrics per month including MoM Revenue Growth, Cumulative Revenue, Avg Sales Cycle
- Traffic-light quota attainment and win rate coloring
- Two embedded charts: Revenue vs Target (column) + Win Rate Trend (line)

### Rep Scorecard
- Full KPI suite per rep: Won Rev, Quota %, Win Rate, Avg Deal Size, Pipeline, Gross Margin, Avg Cycle, ACV
- **5-tier performance classification:** Elite (≥110%) · On Target (≥100%) · Near Target (≥85%) · Below Target (≥70%) · At Risk (<70%)
- Team totals row with blended averages

### Win-Loss Analysis
- Side-by-side win reason + loss reason tables with avg deal size, margin, and ARR lost per reason
- Win Rate matrix: every **Segment × Region** combination with avg won and lost revenue, revenue at stake
- Loss reasons: Price, Competitor, No Decision, Budget Cut, Wrong Fit, Timing

### Deal Velocity
- Sales cycle benchmarked across 4 dimensions: **Segment, Region, Lead Source, Product Category**
- Avg Days (Won) vs Avg Days (Lost) with velocity gap calculation
- **Bottleneck Flag:** 🟢 On Track (<60 days) · 🟡 Review (60–90) · 🔴 Slow Close (>90)

### Cohort Analysis
- **Monthly cohort matrix:** 12 months × 12 metrics — Win Rate, Loss Rate, Avg Rev, Margin, Cycle, Top Product, Top Lead Source, Weighted Pipeline
- **Quarterly summary:** Q1–Q4 with New Logo vs Expansion revenue split, total deals, margin %

### Pipeline & Forecast
- Stage conversion funnel with automatic **bottleneck detection** (conversion <60% from prior stage)
- Forecast categories: Commit / Best Case / Pipeline / Omit with risk level flags
- **3-scenario revenue model:** Base Case, Optimistic, Conservative — each with Weighted Rev, Commit $, Best Case $, Confidence %, vs Target %

### Product Analysis
- 8 products across 5 categories (SaaS Core, BI, Security, Infrastructure, Services, Developer)
- Win Rate, Revenue, Avg Deal Size, Units, Avg Discount, Gross Margin, Revenue Rank, Cross-Sell Rate per product

### Regional Analysis
- 5 regions: North America, EMEA, APAC, LATAM + sub-breakdowns
- Per region: Win Rate, Revenue, Quota Attainment, Avg Deal Size, Gross Margin, Weighted Pipeline, % of Total

### Lead Source & Industry
- 8 lead sources ranked by **Revenue per Lead** (quality score)
- Metrics: Win Rate, Avg Deal Size, Avg Sales Cycle, Revenue per Lead
- 10 industries ranked by Revenue and Win Rate

---

## 🚀 How to Use

1. **Enable Editing** when opening (Excel Protected View)
2. **Replace Deal Data** with your actual deals — keep headers, replace rows
3. **All metrics recalculate** from the Deal Data sheet automatically
4. **Adjust thresholds** in each sheet's column headers to match your business (e.g. quota tier cut-offs, cycle time benchmarks)
5. **Paste charts** from sub-sheets into the Executive Dashboard chart zones

---

## 📐 Technical Specifications

| Attribute | Detail |
|-----------|--------|
| **Format** | `.xlsx` — Excel 2016+, Excel 365, Google Sheets |
| **Macros** | None |
| **Add-ins** | None |
| **Rows of deal data** | 500 deals |
| **Fields per deal** | 29 |
| **Sales reps** | 12 (across 4 regions, 3 segments) |
| **Products** | 8 (across 5 categories) |
| **Industries** | 10 |
| **Lead sources** | 8 |
| **Forecast scenarios** | 3 (Base / Optimistic / Conservative) |
| **Embedded charts** | 2 (Monthly Rev vs Target, Win Rate Trend) |
| **Sheets** | 12 |

---

## 🧰 Analytics Techniques Used

- Weighted pipeline value (`Deal Value × Close Probability`)
- Velocity gap analysis (`Avg Days Lost − Avg Days Won`)
- Cohort analysis by month and quarter
- Cross-sell rate calculation per product
- Source quality scoring (`Revenue per Lead`)
- Scenario modeling (Base / Optimistic / Conservative)
- Bottleneck detection (stage conversion <60%)
- 5-tier performance classification with dynamic thresholds
- Segment × Region win rate matrix
- New Logo vs Expansion revenue segmentation
- Gross margin by product, rep, and region
- MoM revenue growth with directional color coding
- Cumulative revenue tracking
- ACV and ARR tracking per deal

---

## 📊 Key Metrics Reference

| Metric | Formula |
|--------|---------|
| Quota Attainment | Won Revenue ÷ Target |
| Win Rate | Closed Won ÷ (Closed Won + Closed Lost) |
| Weighted Pipeline | Σ (Deal Value × Close Probability) for open deals |
| Avg Sales Cycle | Σ Days Open (Won) ÷ Won Count |
| Gross Margin % | Gross Margin $ ÷ Revenue |
| Velocity Gap | Avg Days (Lost) − Avg Days (Won) |
| Revenue per Lead | Total Won Revenue ÷ Total Deals from Source |
| Cross-Sell Rate | Reps selling that product with >1 product ÷ Total Reps |
| ARR | ACV × ~1.0 (annualized contract value) |
| Forecast Confidence | Commit: 90% · Best Case: 45% · Pipeline: 70% Base |

---

## 🔄 Compatibility

| Platform | Status |
|----------|--------|
| Microsoft Excel 2016+ | ✅ Full |
| Microsoft Excel 365 | ✅ Full |
| Google Sheets | ✅ Compatible (re-insert charts) |
| LibreOffice | ⚠️ Minor formatting differences |

---

## 📜 License

MIT License — free to use, adapt, and redistribute.

---

*Built with Python (xlsxwriter). Connect on [LinkedIn](https://www.linkedin.com/in/ehsan-zim) or open an issue.*
