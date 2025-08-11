# CUSM Library & Student Engagement Dashboard

A simple, three-page Power BI report that tracks library usage and resource demand. It’s built to be easy to refresh, easy to read, and useful for quick decisions.

## What’s inside

* **Overview:** big-picture traffic and usage
* **Library:** top titles, categories, and monthly patterns
* **Students:** entry trends by month/quarter with “busiest periods” callouts
* **Auto-refresh:** scheduled updates so metrics stay current

## Key features

* Clear KPIs (e.g., total entries, unique item requests, top month)
* Actionable visuals (Top N titles, category mix, monthly trends)
* Drill-through from high-level metrics to specific titles or months
* Refresh-ready Power Query steps and parameters

## Pages & KPIs

### 1) Overview

* **KPIs:** Total Entries, Total Item Requests, Top Month, % change vs. prior period
* **Visuals:** monthly traffic trend, category donut, top titles bar

### 2) Library

* **KPIs:** Top Title Requests, % of usage by category (Books/Journals/Reports)
* **Visuals:** Top 10 titles, category share, monthly item requests
* **Insight callouts:** “Skew toward a few core titles,” “Seasonal peaks in late summer/fall”

### 3) Students

* **KPIs:** Total Entries, Top 3 Months, Quarter share of traffic
* **Visuals:** monthly entries, quarter breakdown, YoY change marker
* **Insight callouts:** “>2× increase year over year,” “October is the busiest month”

## Data inputs

Place source files in a `/data` folder (or your SharePoint/OneDrive path):

* Visitor logs (weekly/monthly entries)
* COUNTER reports (platform/title usage exports)
* Optional lookup tables (date table, category mappings)

**Tip:** Keep consistent column names across files (e.g., `Date`, `Entries`, `Title`, `Requests`, `Category`).
