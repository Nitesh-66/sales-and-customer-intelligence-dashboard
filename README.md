# 📊 SALES & CUSTOMER INTELLIGENCE DASHBOARD

##  Project Overview

This project focuses on building an interactive and scalable **Power BI dashboard** using a structured data model, advanced DAX calculations, and modern visualization techniques. The goal is to analyze sales performance, customer behavior, and regional trends to generate actionable business insights.

---

##  Objectives

* Build a robust **data model using Star Schema**
* Create and optimize **DAX measures and KPIs**
* Apply **Time Intelligence functions**
* Develop an **interactive multi-page Power BI report**
* Ensure **mobile compatibility and enhanced user experience**

---

##  Dataset Overview

The project uses multiple tables imported from Excel:

* `Date_Dim`
* `Customer_Dim`
* `Product_Dim`
* `Sales_Fact`
* `Returns_Fact`
* `Region_Dim`

---

##  Data Modeling

* Implemented **Star Schema**
* Established relationships using **Primary & Foreign Keys**
* Fact Tables:

  * Sales_Fact
  * Returns_Fact
* Dimension Tables:

  * Date, Customer, Product, Region

---

##  DAX Measures & Calculations

### 🔹 Key Measures

* Total Sales
* Total Profit
* Total Orders
* Total Returns
* Profit Margin
* Average Sales

###  Advanced Logic

* KPI Classification using `SWITCH`
* Data relationships using `RELATED`
* Aggregations using `CALCULATE`, `SUMX`, `COUNTX`, `AVERAGEX`

###  Calculated Columns

* Customer Full Name
* Year-Month Format
* Profit Category

---

##  Time Intelligence

* Year-to-Date (YTD)
* Month-over-Month (MoM)
* Year-over-Year (YoY)
* Seasonal trend analysis

---

##  Dashboard Structure

* KPI Cards (Sales, Profit, Orders, Returns)
* Line Chart (Sales Trend)
* Bar Chart (Category-wise Sales)
* Donut Chart (Region-wise Distribution)

---

##  Filters & Interactions

* Slicers:

  * Product
  * Customer Segment
  * Region
  * Date
* Drill Down / Drill Up functionality
* Top N filtering (Top Products & Customers)

---

##  Mobile Optimization

* Dedicated mobile layout
* Optimized placement of:

  * KPI Cards
  * Key visuals
* Improved readability and usability

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Refresh data if needed
3. Use slicers to filter insights
4. Navigate between pages using buttons
5. Drill down into visuals for deeper analysis

---

