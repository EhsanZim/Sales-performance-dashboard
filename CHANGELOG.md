# Changelog

## [2.0.0] — 2024-06-07

### Complete Rebuild from v1.0

#### Data Scale
- Expanded from 96 rows to **500 deals**
- Increased from 8 to **12 sales reps** across 4 regions and 3 segments
- Added **29 deal fields** (up from 15): ACV, ARR, CSAT, NPS, Forecast Category, Customer Type, Close Probability, Win/Loss Reason, Industry, Gross Margin, List Price, Discount %
- Added **8 products** across 5 categories with realistic margin profiles
- Added **10 industries** and **8 lead sources**
- Seasonal revenue patterns and segment-based pricing built into data generation

#### New Sheets
- **Win-Loss Analysis** — Win/loss reasons with avg deal metrics; Segment × Region win rate matrix
- **Deal Velocity** — Sales cycle benchmarking across Segment, Region, Lead Source, Category; bottleneck detection
- **Cohort Analysis** — Monthly and quarterly cohort matrices; New Logo vs Expansion split
- **Pipeline & Forecast** — Stage funnel with conversion rates; forecast categories; 3-scenario model
- **Lead Source & Industry** — Source quality scoring by Revenue per Lead; industry win rate rankings

#### Enhanced Existing Sheets
- **Executive Dashboard** — Expanded from 4 to 8+8 KPI cards; 8 chart zones (up from 4)
- **Monthly Trend** — Added MoM Growth, Cumulative Revenue, ACV, Avg Sales Cycle (15 metrics vs 8)
- **Rep Scorecard** — Added Pipeline, ACV, Margin, Sales Cycle; 5-tier classification (was 4)
- **Product Analysis** — Added Cross-Sell Rate, Avg Discount, Revenue Rank
- **Regional Analysis** — Added Weighted Pipeline, Quota Attainment, Gross Margin per region

#### Technical
- Rebuilt with xlsxwriter for guaranteed color rendering in all Excel versions
- Realistic seasonal patterns (sin-wave + Q4 surge) in revenue generation
- Probability-weighted pipeline values throughout
- MIT License

---

## [1.0.0] — 2024-05-01
- Initial release: 96 rows, 8 reps, 6 sheets
