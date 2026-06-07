# Changelog

All notable changes to the Sales Performance Dashboard will be documented here.

## [1.0.0] — 2024-06-07

### Added
- Initial release of the Sales Performance Dashboard workbook
- **Executive Dashboard** sheet with 4 live KPI cards (Revenue, Quota Attainment, Deals Closed, Avg Deal Size)
- **Raw Data** sheet with 96 rows of sample data across 12 months and 8 sales reps, 15 tracked fields
- **Monthly Trend** sheet with MoM growth calculation and conditional formatting traffic lights
- **Regional Analysis** sheet with dynamic RANK formula and attainment color flags
- **Rep Performance** sheet with auto-assigned performance tier (Elite / High Performer / On Track / Needs Attention)
- **Pipeline** sheet with weighted forecast value using stage-based conversion rates
- **Instructions** sheet with full workbook guide
- Color-coded tab system for easy navigation
- Auto-filter and freeze panes on Raw Data sheet
- Clustered bar chart (Revenue vs. Target) on Monthly Trend sheet
- Color scale conditional formatting on Pipeline weighted values
- Cross-sheet formula architecture — all sheets recalculate from Raw Data automatically
- Zero formula errors across 312 dynamic formulas (verified)

### Technical
- Built with openpyxl; compatible with Excel 2016+, Excel 365, and Google Sheets
- No macros or add-ins required
- MIT License

---

## Planned for Future Versions

- [ ] v1.1.0 — Product-level breakdown sheet
- [ ] v1.1.0 — Lead source analysis tab
- [ ] v1.2.0 — Quarter-over-quarter comparison view
- [ ] v1.2.0 — Dynamic date filter using slicers (Excel 365)
- [ ] v1.3.0 — Customer type segmentation analysis
- [ ] v2.0.0 — Power Query version for automated data refresh
