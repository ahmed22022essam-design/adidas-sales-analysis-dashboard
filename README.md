1. Repo name

adidas-sales-analysis-dashboard

Other options if you prefer:

adidas-us-interactive-sales-dashboard
adidas-sales-excel-dashboard

2. Description (about 295 characters)

Excel sales analysis and interactive dashboard for Adidas across Egypt, Iraq, Oman, KSA and Lebanon (2023–Q3 2025). Includes pivot tables, a KPI dashboard with slicers, and a management presentation covering revenue, profit, channels, products and payment methods, with actionable recommendations.

Suggested topics (to paste in the repo's topics field):
data-analysis excel dashboard sales-analytics pivot-tables data-visualization business-intelligence adidas powerpoint

readme file 
For repo in githup 
As source code

Preparing the README content for display as raw source.

Here is the README as raw Markdown source, ready to copy into your repo's README.md. I updated it with the repo name adidas-sales-analysis-dashboard. The same content is in the README.md file I attached earlier.

markdown
# Adidas Sales Analysis Dashboard

An Excel-based sales analysis project covering **1,200 orders** and **3,550 units** across five markets (Egypt, Iraq, Oman, KSA, Lebanon) from **Q1 2023 to Q3 2025**. The project includes an interactive dashboard, the supporting pivot tables, and a management presentation that turns the numbers into decisions.

## Table of Contents

- [Overview](#overview)
- [Key Metrics](#key-metrics)
- [Key Insights](#key-insights)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Dashboard Features](#dashboard-features)
- [Recommendations](#recommendations)
- [Data Notes and Limitations](#data-notes-and-limitations)
- [Tools Used](#tools-used)
- [Author](#author)

## Overview

**Goal:** help management decide where to focus resources (category, market, channel, product) and how to respond to the slowdown in 2024.

**Questions answered**

1. Which categories, markets, channels and products drive revenue and profit?
2. How has revenue changed over time?
3. Which payment methods do customers use?
4. What should the business do next?

## Key Metrics

| Metric | Value |
|---|---|
| Total revenue | 287,378 |
| Total profit | 85,070 |
| Profit margin | 29.6% |
| Total orders | 1,200 |
| Units sold | 3,550 |
| Average order value | ≈ 240 |
| Average profit per order | ≈ 71 |

## Key Insights

- **Footwear drives revenue:** 62% of revenue (179,006), followed by Apparel (27%) and Accessories (11%).
- **Accessories have the best margin:** 32.9%, compared with 29.5% for Footwear and 28.5% for Apparel.
- **Revenue is concentrated geographically:** Egypt, Iraq and Oman generate 82% of revenue. KSA contributes 11.5% and Lebanon 6.1%.
- **Online is the leading channel:** Online 46%, Retail 36%, Outlet 12%, Wholesale 6%.
- **Two products lead:** Predator Freak and Ultraboost Light account for 21.5% of revenue; the top 10 products account for 82%.
- **Revenue peaked in 2023:** 2024 revenue was 3.8% lower than 2023. Q4 2024 was 16% below Q4 2023, while Q3 2025 was 14% above Q3 2024.
- **Payments are balanced:** eight methods, each between 11% and 14% of orders.

## Repository Structure

```
.
├── README.md
├── data/
│   └── Adidas-US-Interactive-Sales-Project.xlsx   # Data, pivot tables, dashboard
├── presentation/
│   ├── Adidas_Sales_Management_Deck_EN.pptx       # 14-slide management deck
│   └── Adidas_Sales_Management_Deck.pptx          # Arabic version
└── images/
    ├── dashboard.png                              # Dashboard screenshot
    ├── pivot-tables.png                           # Pivot tables screenshot
    └── icons/                                     # KPI icons (4 files)
```

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/<your-username>/adidas-sales-analysis-dashboard.git
   cd adidas-sales-analysis-dashboard
```
2. Open `data/Adidas-US-Interactive-Sales-Project.xlsx` in Microsoft Excel.
3. Use the slicers on the dashboard sheet to filter by **Category**, **Store Type** and **Order Date**. If the pivot tables do not update, go to **Data → Refresh All**.
4. Open the `.pptx` files in `presentation/` to view the management deck.

**Requirements:** Microsoft Excel 2016 or later (slicers and timelines are required for full interactivity) and PowerPoint for the deck.

## Dashboard Features
<img width="1112" height="516" alt="Screenshot 2026-10-05 105902_edited" src="https://github.com/user-attachments/assets/25ddd5ae-f931-47b8-a1bc-786df826ab3e" />
- KPI cards: Total Sales, Total Orders, Profit, Units Sold
- Sales by category (doughnut), region (pie), method (pie)
- Quarterly sales trend (line)
- Top 10 products by revenue (bar)
- Payment method distribution (column)
- Slicers for Category and Store Type, and a timeline for Order Date

## Recommendations

1. **Protect the core:** Footwear, the Online channel and the leading products.
2. **Diagnose the 2024 decline** (pricing, seasonality, campaigns) before planning 2026.
3. **Expand selectively in KSA** and assess the viability of Lebanon.
4. **Grow Accessories** for their higher margin.

## Data Notes and Limitations

- 2025 data covers **Q1 to Q3 only**, so year-over-year comparisons for 2025 use matching quarters.
- No per-product cost data is available, so margin is analysed at category level.
- The **Total Sales** card on the original dashboard shows 235,433, which equals the sum of the top 10 products only. The full total across all orders is **287,378**; the card's source should be corrected.
- Percentages in this document were calculated from the pivot tables and may differ slightly from dashboard labels due to rounding.

## Tools Used

- Microsoft Excel (data model, pivot tables, slicers, charts)

## Author

**Your Name**
[LinkedIn](linkedin.com/in/ahmed-essam-7482831b3) · [Email](ahmed22022essam@gmail.com)

## License
