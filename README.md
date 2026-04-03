# Data Analysis using Excel
# 📊 Sales Executive Performance Dashboard

## Overview

This Power BI dashboard provides a comprehensive view of **Sales Executive performance** across multiple Indian cities. It tracks total sales figures, target achievement rates, and the gap between actuals and targets — enabling quick identification of top performers and underperformers.

---

## Dashboard Structure

The dashboard is divided into **4 panels (Dboard 1 – Dboard 4)**, each offering a different analytical lens:

| Panel | Focus Area | Visualization Type |
|---|---|---|
| Dboard 1 | Total Sales by Executive | Table + Horizontal Bar Chart |
| Dboard 2 | Total Sales (Secondary Region) | Table |
| Dboard 3 | Target Hit % by Executive | Table + Pie Chart |
| Dboard 4 | Away From Target % | Table + Line Chart |

---

## Filters & Slicers

### City Filter
Users can filter the entire dashboard by selecting one or more cities:

`Chennai` | `Delhi` | `Mumbai` | `Nagpur` | `Patna` | `Pune` | `Ranchi` | `Surat`

> Currently selected: **Delhi** (orange highlight) and **Patna** (purple highlight)

---

## Key Metrics

### Dboard 1 — Total Sales (Primary Region)

Displays individual sales executive totals and a grand total.

| Sales Executive | Total Sales |
|---|---|
| Anikuttan | 382 |
| Ritu Bhatnagar | 371 |
| Rashid | 340 |
| ManjuTiwari Lab | 318 |
| Bhagwat Singh | 327 |
| Kisun Sah | 286 |
| Shashikant Tiwari | 276 |
| Sonaram Munda | 291 |
| Rajendra Kumar | 292 |
| Anoop Raj | 307 |
| **Grand Total** | **3190** |

**Visualization:** Horizontal bar chart sorted by sales volume, with color gradient (light to dark blue) to indicate performance ranking.

---

### Dboard 2 — Total Sales (Secondary Region)

| Sales Executive | Total Sales |
|---|---|
| Indra Pal | 243 |
| Jyoti Tulsani | 228 |
| Kisun Sah | 286 |
| Mubeen Khan | 209 |
| Om Prakash | 254 |
| Praveen Kumar | 166 |
| Sanjiv Subherwal | 223 |
| Shashikant Tiwari | 276 |
| Sushma Khandelwal | 213 |
| Tanuja Kale | 239 |
| **Grand Total** | **2337** |

---

### Dboard 3 — Target Hit % (How close to target?)

Measures what percentage of the sales target each executive achieved.

| Sales Executive | Target Hit % |
|---|---|
| Rashid | 68.00% |
| Anikuttan | 76.40% |
| Ritu Bhatnagar | 74.20% |
| Anoop Raj | 61.40% |
| Bhagwat Singh | 65.40% |
| ManjuTiwari Lab | 63.60% |
| Kisun Sah | 57.20% |
| Rajendra Kumar | 58.40% |
| Shashikant Tiwari | 55.20% |
| Sonaram Munda | 58.20% |
| **Grand Total** | **638.00%** |

**Visualization:** Pie chart showing each executive's proportional share of cumulative target hits. Top performers: Anikuttan (12%), Ritu Bhatnagar (12%), Rashid (11%).

---

### Dboard 4 — Away From Target % (Gap analysis)

Shows how far each executive is from fully achieving their target — lower is better.

| Sales Executive | Away From Target % |
|---|---|
| Praveen Kumar | 66.80% |
| Mubeen Khan | 58.20% |
| Jyoti Tulsani | 54.40% |
| Indra Pal | 51.40% |
| Sushma Khandelwal | 57.40% |
| Om Prakash | 49.20% |
| Sanjiv Subherwal | 55.40% |
| Shashikant Tiwari | 44.80% |
| Tanuja Kale | 52.20% |
| Kisun Sah | 42.80% |
| **Grand Total** | **532.60%** |

**Visualization:** Line chart showing the "away from target" trend across all executives. Praveen Kumar has the highest gap (66.80%); Kisun Sah has the smallest gap (42.80%).

---

## Key Insights

- **Top Performer (Sales Volume):** Anikuttan with 382 total sales.
- **Highest Target Achievement:** Anikuttan at 76.40% of target hit.
- **Furthest from Target:** Praveen Kumar at 66.80% away from target.
- **Closest to Target:** Kisun Sah at only 42.80% away — meaning they are the most target-efficient in Dboard 4.
- **Combined Grand Total Sales:** 3190 (primary) + 2337 (secondary) = **5527 across both regions.**

---

## Tools & Technologies

- **Visualization Tool:** Microsoft Power BI
- **Data Source:** Sales CRM / Internal Records
- **Regions Covered:** 8 cities across India
- **Executives Tracked:** 10 per panel

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the **city slicer** at the top to filter by region.
3. Use the **Dboard checkboxes** to toggle individual panels.
4. Hover over charts for exact values and tooltips.
5. Publish to Power BI Service for team-wide access and scheduled refresh.

---

## File Structure

```
sales-dashboard/
├── README.md                  ← This file
├── SalesDashboard.pbix        ← Power BI report file
├── data/
│   └── sales_data.xlsx        ← Source data
└── screenshots/
    └── dashboard_overview.png ← Dashboard preview
```

---

## Author

> Built for internal sales performance tracking and executive review.  
> For queries, contact the Data Analytics team.
