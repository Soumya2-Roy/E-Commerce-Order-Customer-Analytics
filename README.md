# E-Commerce Order & Customer Analytics

## 📊 Project Overview

**E-Commerce Order & Customer Analytics** is an Excel-based Business Intelligence and Data Analytics project designed to analyse e-commerce orders, customers, products, regions, payment methods, and order outcomes.

The project transforms transaction-level data into meaningful **KPIs, trends, comparisons, customer insights, and business recommendations** to support data-driven decision-making.

The analysis is based on the provided e-commerce transaction workbook and its supporting dashboard, cleaned data, backend summaries, raw data, and data dictionary.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyse overall e-commerce order and revenue performance.
- Measure important business KPIs such as Net Revenue, Orders, Customers, Quantity Sold, Average Order Value, and Average Rating.
- Identify high-performing regions and geographical markets.
- Analyse category and product-level revenue performance.
- Understand customer behaviour through customer segments, gender, age, and repeat-order patterns.
- Evaluate order performance across Delivered, Returned, Cancelled, and Pending statuses.
- Analyse payment-method usage and revenue contribution.
- Identify business opportunities and operational improvement areas.
- Present the analysis through a professional Excel dashboard.

---

## 📅 Analysis Period

**4 January 2026 – 20 August 2026**

---

## 📌 Dataset Summary

| Metric | Value |
|---|---:|
| Transaction Records | 100 |
| Unique Orders | 100 |
| Unique Customers | 20 |
| Quantity Sold | 257 |
| Number of Columns | 22 |
| Gross Sales | ₹429,243.00 |
| Discount Amount | ₹43,649.40 |
| Shipping Cost | ₹7,550.00 |
| Net Revenue | ₹393,143.60 |
| Average Order Value | ₹3,931.44 |
| Average Rating | 3.98 / 5 |

---

## 📁 Workbook Structure

The Excel workbook contains the following sheets:

### 1. Dashboard

The **Dashboard** sheet provides an executive-level view of the e-commerce business performance.

The main KPI areas include:

- Total Orders
- Customers
- Quantity Sold
- Net Revenue
- Average Order Value
- Average Rating

### 2. CLEAN_Data

The **CLEAN_Data** sheet contains the cleaned transaction-level dataset used for the analysis.

It contains:

- 100 transaction records
- 22 business-related columns

### 3. RAW_DATA

The **RAW_DATA** sheet contains the original transaction-level data used as the source dataset.

### 4. Backend

The **Backend** sheet contains supporting summary and pivot-style calculations used for analysis and dashboard reporting.

### 5. Data_Dictionary

The **Data_Dictionary** sheet provides definitions and meanings for the dataset columns.

### 6. Sheet3

The **Sheet3** sheet contains supporting pivot-style summary information used for analysis.

---

# 🧾 Data Dictionary

| Column | Description |
|---|---|
| Order ID | Unique order number |
| Order Date | Date on which the order was placed |
| Customer ID | Unique customer number |
| Customer Name | Customer name |
| Gender | Customer gender |
| Age | Customer age |
| City | Customer city |
| State | Customer state |
| Region | Geographical region |
| Product | Purchased product |
| Category | Product category |
| Quantity | Number of units purchased |
| Unit Price | Price per unit |
| Discount | Discount percentage |
| Shipping Cost | Shipping charge |
| Payment Method | Payment method used |
| Order Status | Current order status |
| Rating | Customer rating |
| Customer Segment | Customer segment |
| Gross Sales | Quantity × Unit Price |
| Discount Amount | Gross Sales × Discount |
| Net Revenue | Gross Sales − Discount Amount + Shipping Cost |

---

# 📈 Key Performance Indicators

The following KPIs were calculated from the `CLEAN_Data` sheet.

| KPI | Value |
|---|---:|
| **Gross Sales** | ₹429,243.00 |
| **Discount Amount** | ₹43,649.40 |
| **Shipping Cost** | ₹7,550.00 |
| **Net Revenue** | **₹393,143.60** |
| **Total Orders** | **100** |
| **Customers** | **20** |
| **Quantity Sold** | **257** |
| **Average Order Value** | **₹3,931.44** |
| **Average Rating** | **3.98 / 5** |
| **Discount Rate** | **10.17%** |

### KPI Formulas

**Gross Sales**

```text
Quantity × Unit Price
