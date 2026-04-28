# Tableau IT Risk Executive Dashboard Mockup

A polished, Tableau-style **executive IT Risk Management dashboard** built as a standalone HTML prototype for financial services organizations.

## What's inside

| Visualization | Purpose |
|---|---|
| **4 KPI tiles** | Critical risks open, % within appetite, high-severity incidents, control effectiveness |
| **Residual risk heatmap** | Impact × likelihood matrix with color-banded risk zones |
| **Top risk concentrations** | Ranked bar chart by residual score across IT domains |
| **Risk trend vs incidents** | 12-month time series with incident overlays and event markers |
| **Control remediation aging** | Traffic-light status table with open issue counts and oldest age |

## Design principles

- Executive-first: one primary story per screen, 5–7 objects max
- Color semantics: Red = above appetite, Amber = watch, Green = within appetite
- Light **and** dark mode toggle built in
- Fully responsive (desktop, tablet, mobile)
- Zero dependencies — single HTML file, no build tools required

## How to use

1. Open `index.html` directly in any browser — no server needed
2. Use the theme toggle (◐) in the top-right to switch light/dark
3. Adapt the mock data in the HTML to connect your real Tableau data source

## Tableau implementation notes

- Start from the IT Risk Fact table: Risk ID, System, Business Unit, Category, Inherent/Residual Score, Appetite Flag, Owner, Status
- Build worksheets: Risk Heatmap · Top 10 Bar · Risk Trend Line · Controls Heatmap · Issues Aging Bar
- Assemble 3 dashboards: Exec Overview · Top Risks & Concentration · Cyber Risk

## Built by

[Roger I. Garcia](https://rogergarcia.consulting) — Consultant & Digital Strategist, Toronto

---

> This is a visual prototype / concept reference. Not connected to live data.
