# Investors Dashboard

## Why this exists

**Purpose** — This dashboard was built to submit as a report to our current investors on how the business is going. The same dashboard was also used to pitch to new investors.

## Data Sources

## Data Pipeline

Data Pipeline — from the field to the dashboard

```
WMS
 │   Regional teams enter headcount data every week
 ▼
PostgreSQL
 │   System of record — the live database
 ▼
pgAdmin 4 — VIEW
 │   Joins the WMS tables into one output shape
 ▼
Looker Studio
 │   Live connection straight to the view
 ▼
Auto-refresh — every Monday, 9:00 AM
```

## Dashboard Preview

![Investors Dashboard](INVESTORS/Investors_Dashboard_page-0001.jpg)
