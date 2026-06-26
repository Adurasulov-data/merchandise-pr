# Merchandise Sales Analytics Dashboard — Power BI

An interactive Power BI dashboard analyzing merchandise sales performance across product categories, age groups, gender segments, and international markets for 2023–2024.

---

## Dashboard Preview

![Merchandise Sales Analytics Dashboard](screenshots/dashboard.png)

---

## Key Metrics

| Metric | Value |
|--------|-------|
| Total Sales | $856K |
| Total Quantity | 12K |
| Total Orders | 7,394 |
| Date Range | Jan 2024 – Oct 2024 |

---

## Dashboard Features

### 🔽 Interactive Filters
- **Year** slicer — 2023 / 2024
- **Age Group** slicer — 18-24 / 25-34 / 35+

### 📈 Monthly Sales Trend
Line chart tracking monthly revenue across the year. Peak performance in **April ($81K)** and **May ($77K)**, with a notable drop in October ($0K — partial month data).

### 📦 Sales by Product Category
Donut chart breakdown:
- **Clothing** — $637K (74.4%) — dominant category
- **Ornaments** — $156K (18.19%)
- **Other** — $63K (7.41%)

### 🌍 Sales by International Shipping
Bar chart comparing domestic vs. international orders. Domestic (No) orders exceed international (Yes) shipments in total revenue.

### 👥 Sales by Age Group
- **25-34** — highest spending age group (~$400K)
- **18-24** — second highest
- **35+** — smallest segment

### ⚧ Gender Distribution of Buyers
- **Female** — 70.16% ($5.19K avg)
- **Male** — 29.84% ($2.21K avg)

### 🗺️ Sales by Order Location
Interactive world map showing order locations across North America, Europe, Asia, Africa, South America, and Australia.

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development |
| DAX | KPI measures (Total Sales, Quantity, Order Count) |
| Power Query | Data transformation and cleaning |
| Bing Maps | Geographic order visualization |

---

## Project Structure

```
merchandise-sales-dashboard/
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## Key Insights

- **Clothing** dominates at 74.4% of total revenue — core product line driving the business
- **Female buyers** make up over 70% of the customer base — strong gender skew worth leveraging in marketing
- **25-34 age group** is the most valuable segment, outspending other groups significantly
- Sales peaked in **April–May** and declined sharply toward Q4 — possible seasonality pattern
- International shipping orders are lower than domestic — potential growth opportunity in global markets
- Orders span **6 continents**, showing a truly global customer base

---

## Author

Built as a Power BI portfolio project. Feel free to connect or reach out for collaboration!
