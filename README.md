# QSR Franchise Financial Forecasting Model

A five-tab financial forecasting model built for a 10-location,
multi-brand quick-service restaurant portfolio (Little Caesars, Arby's, Wingstop).
Covers new location viability, same-store sales growth, demographic scoring,
and three-case scenario planning across a 5-year horizon.

## Model Structure

| Tab | Purpose |
|---|---|
| **Dashboard** | Global assumptions, portfolio KPI snapshot, 5-year revenue summary |
| **5-Year Forecast** | Annual revenue and EBITDA projection for all 10 locations, 2025–2029 |
| **Location Scoring** | Weighted demographic and competitive scoring matrix per location |
| **New Location Analyzer** | Site viability tool — outputs GO/NO-GO, break-even, payback, and NPV |
| **Scenario Planner** | Base, Upside, and Downside cases with sensitivity analysis |

## Key Features

### New Location Viability
Enter any proposed site's brand, revenue estimate, rent, and cost structure.
The model outputs:
- Year 1 EBITDA and margin
- Break-even month
- Payback period (years)
- 5-year NPV (discounted at your hurdle rate)
- Investment multiple (MOIC)
- Automatic **GO / REVIEW / NO-GO** verdict based on your margin threshold

### Same-Store Sales Growth
Each existing location compounds annually using brand-specific growth rates,
editable from the Dashboard. Outputs include per-location CAGR and 5-year
cumulative revenue by brand.

### Demographic & Competitive Scoring
Four location factors scored 1–10, each independently weighted:
- **Population density** — addressable market size
- **Household income** — purchasing power and ticket size
- **Foot traffic score** — walk-in and impulse visit potential
- **Competitor proximity** — revenue dilution risk

Composite score maps to a revenue adjustment range
(from +15% for exceptional sites to -15% for weak ones).

### Scenario Planning
Three fully independent cases (Base, Upside, Downside) with separate
editable assumptions for revenue growth, food cost, labor, rent escalation,
and marketing spend. Includes a 7-lever sensitivity table showing
EBITDA dollar impact of each key business driver.

## How to Use

1. Open the file and start on the **Dashboard** tab
2. Edit the yellow assumption cells (growth rates, inflation, discount rate,
   margin threshold)
3. Navigate to **Location Scoring** — update demographic scores for each site
4. Use **New Location Analyzer** to evaluate any proposed site
5. Run **Scenario Planner** to stress-test the portfolio under different conditions

All tabs update automatically from Dashboard assumptions.
No macros required — fully formula-driven.

## Tools & Methods

Excel | Financial modeling | Demographic analysis |
DCF / NPV | Scenario planning | QSR operations

## Context

Built to demonstrate financial forecasting and operations analytics skills
developed across fintech, franchise operations, and program management.
Companion file to the
[Franchise P&L Model](https://github.com/YOURUSERNAME/franchise-pl-model).
