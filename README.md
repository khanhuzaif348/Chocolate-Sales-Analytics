# Chocolate-Sales-Analytics
# 🚀 Power BI Sales & Shipment Dashboard

An advanced Power BI dashboard built to analyze **global sales, profit, cost, and shipment trends** interactively.

## 🌟 Key Features
- **Dynamic Dashboard Design**
  - Salesperson-level and Product-level comparison using **Bookmarks**
  - KPI cards for Sales, Boxes, Shipment, Cost, and Profit
- **Interactive Analysis**
  - Monthly trend chart (Sales, Profit%)
  - Shipment performance gauge + distribution histogram
- **Advanced DAX Measures**
  - MoM Sales Growth
  - Profit Margin %
  - Shipment Performance %
- **Tooltips for better visibility**
- **Published via Power BI Service** – view without Power BI Desktop


📊 Visualization Highlights

Dual View Dashboard

👨‍💼 Salesperson Table

🍫 Product Table (via Bookmarks)

Shipment Analysis

Dynamic Gauge + Bar Chart

Interactive Buttons

For switching dashboards and regions

🚀 Deployment

Published via Power BI Service for live access

## 🔗 Live Power BI Dashboard
👉 [Click here to view the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmExMjYwMjAtYThlNC00MTU3LTgyNzgtODczMjVmODljZDdmIiwidCI6ImYwYzJhZDgxLTcxNTUtNGMzYy04OTAyLTNiNDZhYmVlNzIyZSIsImMiOjZ9)


## 🧠 DAX Samples
```DAX
MoM Sales = 
VAR PrevMonth = CALCULATE([Total Sales], DATEADD('Date'[Date], -1, MONTH))
RETURN DIVIDE([Total Sales] - PrevMonth, PrevMonth)

Profit % = DIVIDE([Profit], [Sales])





