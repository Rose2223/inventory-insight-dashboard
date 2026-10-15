# Inventory & Forecasting Cell — Sep 2026 Insight Pack Dashboard

Live dashboard UI for the monthly inventory insight pack.  
**Engine:** Contextflow Holt-Winters v1 · Agent `6ad07a300638a42df94f24ee`  
**Extract:** September 2026 · 491 materials · 6 plants · ZSPR + ZSPN

## Features
- **Dark / Light mode toggle** — CSS custom properties, zero-flash, charts re-render on switch
- **10 KPI tiles** — Gross Inventory, DOH, Turnover, Critical Availability, NMI, Overstock, Understock, PRs, MRP Eligibility, Duplicates
- **2 charts** — Grouped bar (plant forecast) + Doughnut (exposure breakdown)
- **5 alert banners** — 2 critical, 2 high, 1 info
- **4 data tables** — V2 Overstock, V3 Understock, V4 NMI/SMI, V5 PR Recommendations
- **5 recommendation cards** — prioritised actions with deadlines
- **Data provenance footer** — engine, agent ID, run timestamp

## Data Source
All values sourced from live Contextflow MCP forecast engine output.  
Run timestamp: `2026-10-15T07:04:08Z`

## Files
| File | Description |
|------|-------------|
| `index.html` | Single-file dashboard (HTML + CSS + JS, Chart.js 4.4.0 CDN) |

## Usage
Open `index.html` in any modern browser. No build step required.
