# 📊 Sales Performance Dashboard – Regional, Product & Salesperson Analytics

[![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoft-excel)](https://www.microsoft.com/excel)
[![Pivot Tables](https://img.shields.io/badge/Type-Sales_Analytics-blue)](https://github.com)
[![Performance Tracking](https://img.shields.io/badge/Analysis-Sales_Performance-orange)](https://github.com)

A comprehensive Excel solution built to analyze company-wide sales performance and visualize key metrics across product categories, regional distribution, individual salesperson achievement, and monthly sales trends. It transforms raw sales transaction data into actionable insights — enabling decision-makers to quickly assess overall performance, identify top performers, and pinpoint areas needing attention.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Dataset Description](#dataset-description)
- [Excel Techniques Used](#excel-techniques-used)
- [Dashboard Components & Results](#dashboard-components--results)
- [Installation & Prerequisites](#installation--prerequisites)
- [How to Use](#how-to-use)
- [Key Insights](#key-insights)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)

---

## 📊 Project Overview

This Excel project provides an **interactive analysis of company-wide sales performance and achievement metrics** using pivot tables, pivot charts, and dynamic dashboard visualization. It enables monitoring of:

- 🌍 **Sales by region** (East, North, South, West distribution)
- 📦 **Sales by product category** (Beauty, Clothing, Electronics, Furniture, Sports)
- 👥 **Salesperson performance vs target** (Individual achievement and variance tracking)
- 📈 **Monthly sales trends** (Seasonal patterns and monthly performance)
- 💹 **Target achievement** (Variance analysis and team performance)
- 📊 **Performance comparison** (Regional and categorical insights)

---

## 🎯 Project Objective

To analyze company-wide sales performance and visualize key metrics for informed decision-making:

✅ **Assess overall sales performance** across regions and product categories  
✅ **Track individual salesperson achievement** against targets  
✅ **Identify regional performance variations** and top-performing regions  
✅ **Analyze product category contribution** to total revenue  
✅ **Monitor monthly sales trends** and seasonal patterns  
✅ **Enable quick performance assessment** for decision-makers and stakeholders  

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data aggregation, pivot tables, dashboard creation |
| **Pivot Tables** | Sales metrics by region, product, and salesperson |
| **Pivot Charts** | Visual trends (Column, Line, Pie, Bar charts) |
| **Slicers** | Dynamic interactivity for performance filtering |
| **Cell-based Formulas** | Variance calculations and totals |
| **Custom Formatting** | Layout design and data highlighting |

---

## 📋 Dataset Description

### File Details

**File Name:** Sales-Performance-Dashboard-[Excel].xlsx

**Source:** Internal company sales data (sample for analysis)

**Total Records:** 800+

**Total Columns:** 6

### Columns

| Column | Description |
|--------|-------------|
| **Date** | Transaction or performance entry date |
| **Region** | Sales region (East, North, South, West) |
| **Product Category** | Product category classification |
| **Salesperson** | Salesperson name or identifier |
| **Total Sales** | Sales amount in currency (₹) |
| **Target** | Sales target for the period |

### Data Overview

Each record represents a sales transaction or monthly performance entry by salesperson and region, containing sales achievement and target metrics for performance tracking.

---

## ⚙️ Excel Techniques Used

**Data Aggregation**
- Pivot Tables for aggregated metrics by region, product, and salesperson
- Pivot Fields configuration for dimensional analysis

**Analysis & Calculation**
- Cell-based formulas for totals and variance
- Variance % calculation for target achievement tracking

**Visualization**
- Column Charts for regional sales comparison
- Pie Charts for product category distribution
- Horizontal Bar Charts for salesperson performance comparison
- Line Charts for monthly trend analysis

**Interactivity**
- Slicers for dynamic filtering and exploration
- Cross-filter capability across dashboard elements

**Dashboard Design**
- Custom formatting and layout design for clarity
- Consistent visual hierarchy and presentation

---

## 📈 Dashboard Components & Results

### 1️⃣ Sales by Region

**Pivot Fields:** Region → Total Sales

| Region | Total Sales (₹) |
|--------|-----------------|
| **East** | 660,765.02 |
| **North** | 670,334.25 |
| **South** | 653,420.45 |
| **West** | 576,830.59 |
| **Grand Total** | 2,561,350.31 |

**Visualization:** Column Chart

**Key Observations:**
- North Region achieved the highest total sales (₹670K)
- West Region recorded the lowest sales (₹576K)
- All regions contributed relatively evenly, showing balanced market coverage

---

### 2️⃣ Sales by Product Category

**Pivot Fields:** Product Category → Total Sales

| Product Category | Total Sales (₹) |
|------------------|-----------------|
| **Beauty** | 524,197.46 |
| **Clothing** | 497,049.22 |
| **Electronics** | 466,324.10 |
| **Furniture** | 490,560.49 |
| **Sports** | 583,219.04 |
| **Grand Total** | 2,561,350.31 |

**Visualization:** Pie Chart

**Key Observations:**
- Sports products contributed the most to total revenue
- Electronics had the lowest sales among all categories
- Product distribution is fairly consistent across categories with slight dominance by Sports and Beauty

---

### 3️⃣ Salesperson Performance vs Target

**Pivot Fields:** Salesperson → Total Sales, Total Target, Variance %

| Salesperson | Total Sales (₹) | Total Target (₹) | Variance % |
|-------------|-----------------|------------------|------------|
| **Alice** | 318,710.92 | 318,280.05 | +0.14% |
| **Bob** | 350,773.43 | 339,141.82 | +3.43% |
| **Charlie** | 288,927.37 | 288,440.47 | +0.17% |
| **David** | 339,726.00 | 335,385.06 | +1.29% |
| **Eva** | 306,343.28 | 301,470.89 | +1.62% |
| **Frank** | 346,472.79 | 353,028.84 | -1.86% |
| **Grace** | 322,558.68 | 319,457.71 | +0.97% |
| **Helen** | 287,837.84 | 287,385.88 | +0.16% |
| **Grand Total** | 2,561,350.31 | 2,545,290.72 | +0.74% |

**Visualization:** Horizontal Bar Chart

**Key Observations:**
- Bob achieved the highest variance above target (+3.43%)
- Frank was the only salesperson slightly below target (-1.86%)
- Overall, the team exceeded total sales targets by +0.74%, showing consistent and stable performance

---

### 4️⃣ Monthly Sales Trend

**Pivot Fields:** Month (from Date) → Total Sales

| Month | Total Sales (₹) |
|-------|-----------------|
| **Jan 2023** | 195,548.49 |
| **Feb 2023** | 243,357.11 |
| **Mar 2023** | 159,322.49 |
| **Apr 2023** | 221,230.56 |
| **May 2023** | 263,434.02 |
| **Jun 2023** | 205,817.31 |
| **Jul 2023** | 176,090.84 |
| **Aug 2023** | 275,699.64 |
| **Sep 2023** | 190,656.58 |
| **Oct 2023** | 206,540.20 |
| **Nov 2023** | 182,759.85 |
| **Dec 2023** | 240,893.22 |
| **Total** | 2,561,350.31 |

**Visualization:** Line Chart

**Key Observations:**
- August (₹275K) had the highest monthly sales
- March (₹159K) recorded the lowest sales
- Sales trend fluctuates throughout the year, indicating possible seasonality in performance

---

## 💡 Key Insights Summary

| Area | Key Finding |
|------|-------------|
| **Regional Performance** | North leads in total sales; West trails behind |
| **Product Mix** | Sports and Beauty contribute the most revenue |
| **Sales Targets** | 7 out of 8 salespersons met/exceeded targets |
| **Monthly Pattern** | August peaks; March dips in sales |
| **Overall Status** | Company slightly exceeds its overall sales target (+0.74%) |

---

## ⚙️ Installation & Prerequisites

### System Requirements

- **Microsoft Excel** (2016 or later recommended)
- **Windows 10** or later / **macOS** with Excel installed
- **2GB RAM** minimum (4GB+ recommended)
- **100MB** free disk space

### Installation Steps

```
1. Download the Excel File
   → Sales-Performance-Dashboard-[Excel].xlsx

2. Open Microsoft Excel

3. File → Open → Select Sales-Performance-Dashboard-[Excel].xlsx

4. Wait for file to load completely

5. Navigate to Dashboard sheet to view visuals
```

---

## 📊 How to Use

### Accessing the Dashboard

**Step 1: Open the File**
```
Microsoft Excel → File → Open → Sales-Performance-Dashboard-[Excel].xlsx
```

**Step 2: Navigate to Dashboard Sheet**
- Select the Dashboard tab/sheet from the sheet tabs at the bottom
- All visualizations and metrics are displayed on this sheet

**Step 3: Use Interactive Elements**

| Feature | Action |
|---------|--------|
| **Slicers** | Click to filter by Region, Product Category, Salesperson, or Month |
| **Charts** | Click on chart elements to explore filtered data |
| **Column Chart** | View regional sales comparison |
| **Pie Chart** | Explore product category distribution |
| **Bar Chart** | Analyze salesperson performance |
| **Line Chart** | Track monthly sales trends |

### Interpreting the Data

- **Column Chart** → Regional sales comparison and performance ranking
- **Pie Chart** → Product category contribution to total revenue
- **Horizontal Bar Chart** → Individual salesperson achievement relative to targets
- **Line Chart** → Monthly sales trends, seasonality, and performance patterns
- **Slicers** → Filter dashboard by specific segments for deeper analysis

---

## 💡 Key Insights

### Regional Performance

✅ **North Region leads** with ₹670,334.25 in total sales, followed closely by East (₹660,765)

✅ **West Region trails** with ₹576,830.59, indicating potential growth opportunity

✅ **Balanced market coverage** across all regions with relatively even distribution

### Product Category Analysis

✅ **Sports products dominate** with ₹583,219 in revenue, contributing the most to total sales

✅ **Beauty category strong** with ₹524,197, supporting Sports as top revenue driver

✅ **Electronics underperforming** with ₹466,324, lowest among all product categories

### Salesperson Performance

✅ **Bob is top performer** with +3.43% variance above target

✅ **7 out of 8 salespersons** met or exceeded their targets, showing strong team performance

✅ **Frank slightly below target** at -1.86%, requiring performance support

### Monthly Trends

✅ **August peak** with ₹275,699 in sales, indicating strong seasonal demand

✅ **March dip** with ₹159,322 in sales, lowest performing month

✅ **Seasonal fluctuations** visible throughout the year, suggesting need for inventory/staffing planning

### Overall Performance

✅ **Company exceeds targets** with +0.74% overall variance, demonstrating consistent execution

✅ **Stable team performance** with minimal variance across individual salespersons

---

## 🧰 Tech Stack

| Component | Technology |
|-----------|------------|
| **Platform** | Microsoft Excel |
| **Analysis Tool** | Pivot Tables & Pivot Charts |
| **Data Visualization** | Excel Charts (Column, Line, Pie, Bar) |
| **Interactivity** | Slicers & Dynamic Filtering |
| **Data Source** | Internal company sales data |

---

## 📁 Project Files

**File:** `Sales-Performance-Dashboard-[Excel].xlsx`
- Excel workbook with sales data and interactive dashboard
- Contains pivot tables, pivot charts, and complete sales analysis
- Ready for immediate use and stakeholder presentation

---

## 💼 Skills Demonstrated

✅ **Data Cleaning and Sorting** in Excel  
✅ **Pivot Table Creation** for multi-dimensional analysis  
✅ **Pivot Chart Design** for effective visualization  
✅ **Formula-based Variance Calculation** for performance tracking  
✅ **Slicers Implementation** for interactive dashboard filtering  
✅ **Dashboard Layout Design** for clear data presentation  
✅ **Data Visualization** techniques and best practices  
✅ **Sales Analysis** and performance metrics interpretation  
✅ **Performance Tracking** and reporting capabilities  
✅ **Business Reporting** for stakeholder communication  

---

## 📝 Notes

- Dataset contains 800+ sales transaction and performance entries from internal company data
- All pivot tables and charts are production-ready and optimized
- Slicers enable flexible filtering across regions, products, salespersons, and months
- Variance calculations directly compare actual sales to targets for performance evaluation
- Analysis supports management decision-making and performance reviews
- Dashboard clearly identifies top performers, regional leaders, and seasonal patterns

---

*This Excel-based Sales Performance Dashboard demonstrates practical business analytics expertise in sales reporting, combining data aggregation through pivot tables, variance analysis, and interactive visualization to enable data-driven decision-making through comprehensive monitoring of regional performance, product category contribution, individual salesperson achievement, and monthly sales trends.*
