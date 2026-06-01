# 30-dax-Analysis

# 📊 DAX Formulas – Power BI Interview Preparation Project

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Formulas-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

A comprehensive Power BI project demonstrating **30+ DAX formulas** that are most frequently asked in Data Analyst and Power BI Developer interviews. This project covers everything from basic aggregations to advanced time intelligence and statistical calculations — all built on a real sales dataset.

---

## 📁 Project Structure

```
Dax_Formulas.pbix
├── Page 1 – Core Sales & Profitability Measures
└── Page 2 – Advanced Time Intelligence & Analytics
```

---

## 🧮 DAX Measures Covered

The project is organized around a central measures table (`All_Measures`) and covers the following categories:

### 💰 Sales & Revenue Measures
| Measure | Description |
|---|---|
| `Total Sales` | Sum of all sales revenue |
| `Gross Sales` | Revenue before discounts and deductions |
| `Total COGS` | Total Cost of Goods Sold |
| `Total Discount` | Sum of all applied discounts |
| `Discount %` | Discount as a percentage of Gross Sales |
| `Total Shipping` | Total shipping costs |
| `Total GST` | Total Goods & Services Tax |

### 📈 Profitability Measures
| Measure | Description |
|---|---|
| `Total Profit` | Net profit after all deductions |
| `Profit Margin %` | Profit as a percentage of Total Sales |
| `Profit YTD` | Year-to-date cumulative profit |
| `Previous Year Profit` | Profit from the same period last year |
| `YoY Profit Growth %` | Year-over-year profit growth percentage |

### 🗓️ Time Intelligence Measures
| Measure | Description |
|---|---|
| `Sales YTD` | Year-to-date sales using `TOTALYTD` |
| `Sales MTD` | Month-to-date sales using `TOTALMTD` |
| `Sales QTD` | Quarter-to-date sales using `TOTALQTD` |
| `Previous Month Sales` | Sales from the prior month using `PREVIOUSMONTH` |
| `Previous Year Sales` | Sales from the same period last year using `SAMEPERIODLASTYEAR` |
| `MoM Sales Growth %` | Month-over-month sales growth percentage |
| `YoY Sales Growth %` | Year-over-year sales growth percentage |

### 📊 Running & Rolling Calculations
| Measure | Description |
|---|---|
| `Running Total Sales` | Cumulative sales from the start using `CALCULATE` + `FILTER` |
| `Rolling 3 Months Sales Avg` | 3-month rolling average using `DATESINPERIOD` |

### 🛒 Order & Customer Analytics
| Measure | Description |
|---|---|
| `Total Orders` | Count of all orders |
| `Total Customers` | Count of unique customers |
| `Average Order Value` | Total Sales divided by Total Orders using `DIVIDE` |
| `Delivered Orders` | Count of successfully delivered orders |
| `Cancelled Orders` | Count of cancelled orders |
| `Returned Orders` | Count of returned orders |
| `Delivery Success Rate %` | Percentage of orders successfully delivered |
| `Cancellation Rate %` | Percentage of orders cancelled |
| `Return Rate %` | Percentage of orders returned |

---

## 🔑 Key DAX Functions Demonstrated

This project showcases the following DAX functions — commonly tested in interviews:

| Category | Functions Used |
|---|---|
| **Aggregation** | `SUM()`, `SUMX()`, `COUNT()`, `COUNTROWS()`, `AVERAGE()`, `DIVIDE()` |
| **Filter Context** | `CALCULATE()`, `FILTER()`, `ALL()`, `ALLEXCEPT()` |
| **Time Intelligence** | `TOTALYTD()`, `TOTALMTD()`, `TOTALQTD()`, `SAMEPERIODLASTYEAR()`, `PREVIOUSMONTH()`, `DATESINPERIOD()`, `DATEADD()` |
| **Logical** | `IF()`, `SWITCH()`, `IFERROR()` |
| **Iterator** | `SUMX()`, `AVERAGEX()`, `COUNTX()` |
| **Relationship** | `RELATED()`, `RELATEDTABLE()` |
| **Table** | `VALUES()`, `DISTINCT()` |

---

## 📐 Data Model

- **Fact Table:** Sales transactions (orders, revenue, costs, shipping, discounts, GST)
- **Dimension Tables:** Customers, Products, Date
- **Measures Table:** `All_Measures` — a dedicated table housing all DAX measures (best practice for clean model management)
- **Relationships:** Star schema design for optimal DAX performance

---

## 🖥️ Report Pages

### Page 1 – Core KPI Dashboard
Displays KPI cards for all core measures:
- Total Sales, Gross Sales, Total Profit, Total COGS
- Discount %, Profit Margin %, Total GST, Total Shipping
- Total Orders, Total Customers, Average Order Value

### Page 2 – Time Intelligence & Advanced Analytics
Displays KPI cards and a comparison table for:
- YTD / MTD / QTD measures
- MoM and YoY growth metrics
- Running Total Sales (with table drill-down)
- Rolling 3-Month Average
- Order fulfillment metrics (Delivery, Cancellation, Return rates)

---

## 💡 Why This Project?

DAX is one of the most tested skills in Power BI interviews. This project was built to:

- Demonstrate **practical application** of the most commonly asked DAX formulas
- Show understanding of **filter context vs. row context** — a core interview concept
- Cover **time intelligence** functions that distinguish intermediate from advanced users
- Follow **best practices** like a dedicated measures table and star schema design

---

## 🚀 How to Use

1. Download the `Dax_Formulas.pbix` file
2. Open it in **Power BI Desktop** (free download from Microsoft)
3. Navigate between **Page 1** and **Page 2** to explore the measures
4. Click on any visual and go to the **Fields pane** to inspect the DAX formula
5. Open the **Model view** to explore the data relationships

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Star Schema Data Modeling**
- **Power Query (M Language)** for data transformation

---

## 👤 Author

> Feel free to connect or reach out for collaborations and opportunities!

---

## ⭐ If you find this project helpful, consider giving it a star!
