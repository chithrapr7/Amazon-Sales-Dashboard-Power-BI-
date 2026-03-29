# 📊 Amazon Sales Dashboard (Power BI)

## 📌 Problem Statement

Businesses generate massive amounts of sales data, but without proper visualization, it becomes difficult to extract meaningful insights.

The objective of this project is to:

* Analyze Amazon sales data across different regions, categories, and time periods
* Identify trends in sales, profit, and customer behavior
* Provide an interactive dashboard to support data-driven decision making

---

## 🎯 Project Objectives

* Track **total sales, profit, orders, and product distribution**
* Analyze **sales trends over time (monthly & yearly)**
* Compare performance across **regions, states, and segments**
* Understand **customer purchasing behavior**
* Identify **top-performing categories and sub-categories**

---

## 📂 Dataset Information

* **File Name:** `Amazon Store Sales Data.xlsx`
* Contains:

  * Order details
  * Product categories & sub-categories
  * Sales, profit, and quantity
  * Customer segments
  * Payment modes
  * Geographic data (state/region)

---

## 🛠️ Tools & Technologies Used

* **Power BI** – Dashboard creation & visualization
* **Excel** – Data source
* **DAX (Data Analysis Expressions)** – Measures & calculations
* **Data Cleaning & Transformation** – Power Query

---

## 📊 Dashboard Overview

The dashboard provides a complete business overview through the following sections:

### 🔹 Key Metrics

* Total Sales: **1.57M**
* Total Profit: **0.18M**
* Total Orders: **3003**
* Total Products: **1755**

---

### 🔹 Sales Analysis

* Sales trend by **Month & Year**
* Seasonal fluctuations and growth patterns

---

### 🔹 Category Insights

* Sales by Category:

  * Office Supplies
  * Technology
  * Furniture
* Sub-category performance:

  * Phones
  * Chairs
  * Binders

---

### 🔹 Customer Segmentation

* Consumer
* Corporate
* Home Office

---

### 🔹 Order Insights

* Order Status:

  * Delivered (Majority)
  * Returned
* Payment Modes:

  * COD
  * Online
  * Cards

---

### 🔹 Geographic Analysis

* Sales distribution across **U.S. states**
* Region-based filtering:

  * Central
  * East
  * South
  * West

---

## 📈 Key Insights

* **Consumer segment** contributes the highest sales
* **Technology category** performs strongly compared to others
* Majority of orders are **successfully delivered (~95%)**
* **COD is the most used payment method**
* Sales show **consistent growth with seasonal spikes**

---

## 🧠 DAX Measures Used

Examples of calculations implemented:

* Total Sales = `SUM(Sales)`
* Total Profit = `SUM(Profit)`
* Total Orders = `COUNT(Order ID)`
* Category-wise and segment-wise aggregations
* Time-based trend analysis

---

## 🚀 How to Use the Dashboard

1. Open the `.pbix` file in Power BI Desktop
2. Use **region filters** to analyze specific areas
3. Interact with charts to drill down into insights
4. Hover over visuals for detailed information

---

## 📌 Project Files

* `Amazon Sales Dashboard.pbix` – Power BI Dashboard
* `Amazon Store Sales Data.xlsx` – Dataset

---

## ✅ Conclusion

This dashboard transforms raw sales data into actionable insights. It enables businesses to:

* Monitor performance in real-time
* Identify profitable segments and categories
* Understand customer behavior
* Make data-driven strategic decisions

---
