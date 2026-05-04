# Operational KPI Monitoring & Process Quality Dashboard
**Live Dashboard → [View Here](https://saivarnika-ba.github.io/kpi-monitoring)**

> Built with Power BI · DAX Time Intelligence · SQL · Excel Automation · Root Cause Analysis

---

## Business Problem
A 2,000+ record operations team tracked SLA compliance, error frequency, and average turnaround time manually across 4 separate weekly Excel reports — slow, error-prone, and giving managers no real-time visibility to act before SLAs were breached.

## What I Built
- **KPI tracking report** monitoring SLA compliance rates, error frequency, and average turnaround time
- **DAX time-intelligence measures** — MTD, QTD, and rolling 12-week averages for trend detection
- **Dynamic filtering** via Power BI bookmarks and slicers — filter by team, time period, and KPI
- **Automated 4 weekly manual Excel reports** by replacing them with scheduled Power BI refresh
- **Root cause analysis layer** — decomposition tree visual to drill into error spikes by team and category

## Key Results
| Metric | Before | After | Change |
|---|---|---|---|
| Quality Score | 82% | 94% | **+12 percentage points** |
| Error Rate | Baseline | Post-action | **-72% reduction** |
| Manual Reporting Effort | 4 Excel reports/week | Automated | **-40% time saved** |
| Report Freshness | Weekly static | Scheduled live refresh | **Real-time** |

## How the Root Cause Was Found
The dashboard surfaced that errors were concentrated in one team during a specific shift window — not a skills problem, but a handover gap. That insight came directly from the decomposition tree visual and was not visible in the flat Excel reports.

## Technical Stack
| Layer | Tool |
|---|---|
| Data Source | SQL — aggregations, joins across operational tables |
| Time Intelligence | DAX — TOTALMTD, TOTALQTD, DATESINPERIOD, rolling averages |
| Interactivity | Power BI Bookmarks, Slicers, Drill-through |
| Automation | Scheduled Power BI Refresh — replaced 4 manual Excel exports |
| Root Cause | Decomposition Tree, Waterfall Chart |

## Files in This Repo
```
index.html          → Live interactive dashboard (open in browser)
README.md           → This file
```

## Skills Demonstrated
`Power BI` `DAX Time Intelligence` `MTD` `QTD` `SQL` `KPI Tracking` `SLA Monitoring` `Excel Automation` `Root Cause Analysis` `Process Improvement`

---
*Part of my analytics portfolio → [saivarnika-portfolio.netlify.app](https://saivarnika-portfolio.netlify.app)*# operations-kpi-monitoring
