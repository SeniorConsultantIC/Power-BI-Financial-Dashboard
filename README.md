# Power BI Financial Dashboard – 5 Pages × (5 Cards + 4 Charts)

## 📊 Project Overview

A complete Power BI report built with **only default visuals** featuring **5 analysis pages**, each with **5 cards** and **4 charts** – totaling **50 visuals** and **30+ DAX measures**.

### Data Source
Microsoft Financial Sample Excel Workbook

### Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Default Power BI Visuals (no custom visuals)

---

## 📄 Report Pages

| Page | Focus | Cards | Charts |
|------|-------|-------|--------|
| 1 | Executive Summary | KPIs (Sales, Profit, Margin, Units, Discount) | Column, Pie, Bar, Line,  |
| 2 | Product Analysis | Product metrics & top performers | Bar, Stacked Column, Scatter, Ribbon,  |
| 3 | Segment & Country | Geographic & segment performance | Column, Bar, 100% Stacked, /Table, Matrix |
| 4 | Time & Trends | MTD, YTD, MoM, YoY trends | Line, Area, Column, Line+Column |
| 5 | Profitability | Gross profit, discount impact | Column, Stacked Column, Scatter, Line,  |

---

## 📐 DAX Measures Included

### Base Measures
- Total Sales, Total Profit, Total Units, Total Discounts
- Profit Margin %, Discount %, Average Price per Unit, Profit per Unit

### Time Intelligence
- Sales MTD, QTD, YTD
- Sales Previous Month/Year
- MoM Growth %, YoY Growth %
- Running Total Sales, Monthly Avg Sales

### Product Analysis
- Top/Bottom Product by Sales
- Product Count, Avg Sales per Product
- High Performers Count, Product Profit Rank

### Segment & Country
- Segment/Country Count
- Top Segment Sales
- International Sales %, USA vs International

### Profitability
- Gross Profit, Gross Margin %
- Discount Impact ($ and %)
- Discount Efficiency, Profit Impact from Discounts
- Discount Bin (calculated column)

---

## 🚀 How to Use

### Prerequisites
- Power BI Desktop (October 2024 or later)

### Steps
1. Download `Financial_Sample_Report.pbix` from the `Report/` folder
2. Open with Power BI Desktop
3. Data is embedded – no additional connections needed
4. Refresh if needed: Home → Refresh

### Calendar Table
The report includes a pre-built Calendar table for time intelligence:
- Marked as official date table
- Columns: Date, Year, Month, Quarter, Week, Day, Is Weekend



## 📝 License

This project is for learning and portfolio purposes. Data source: Microsoft Financial Sample.

---

## 📁 Repository Structure
