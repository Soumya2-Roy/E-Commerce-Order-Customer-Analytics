# E-Commerce Order & Customer Analytics

## 📌 Project Overview

**E-Commerce Order & Customer Analytics** is an Excel-based business intelligence project designed to analyse e-commerce orders, customer behaviour, product performance, regional sales, payment methods, and order outcomes.

The project transforms transaction-level data into meaningful **KPIs, trends, comparisons, business insights, and recommendations** to support data-driven decision-making.

The analysis is based on the provided Excel workbook containing cleaned transaction data, raw data, dashboard metrics, backend summaries, and a data dictionary.




---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyse overall e-commerce order and revenue performance.
- Measure key business KPIs such as Net Revenue, Orders, Customers, Quantity Sold, Average Order Value, and Average Rating.
- Identify high-performing regions, categories, and products.
- Analyse customer behaviour using Customer Segments, Gender, Age, and repeat-order patterns.
- Evaluate order performance based on Delivered, Returned, Cancelled, and Pending statuses.
- Analyse revenue and order contribution by Payment Method.
- Identify important business opportunities and operational improvement areas.
- Present the findings through a professional Excel dashboard.

---
---

## 📊 Dashboard Preview

The project includes an Excel-based interactive dashboard designed to provide a clear and management-friendly view of e-commerce performance.

### E-Commerce Order & Customer Analytics Dashboard

![E-Commerce Order & Customer Analytics Dashboard](images/dashboard.png)

The dashboard provides a consolidated view of:

- Net Revenue
- Total Orders
- Customers
- Quantity Sold
- Average Order Value
- Average Rating
- Monthly Performance
- Regional Performance
- Category Performance
- Product Performance
- Customer Segments
- Order Status
- Payment Methods
- Customer Demographics

---

## 📊 Dataset Information

### Analysis Period

**4 January 2026 – 20 August 2026**

### Dataset Size

| Metric | Value |
|---|---:|
| Transaction Records | 100 |
| Unique Orders | 100 |
| Unique Customers | 20 |
| Quantity Sold | 257 |
| Data Columns | 22 |

---

## 📁 Workbook Structure

The Excel workbook contains the following sheets:

### 1. Dashboard

The **Dashboard** sheet provides the executive-level view of the e-commerce analysis.

It presents the major KPIs:

- Total Orders
- Customers
- Quantity Sold
- Net Revenue
- Average Order Value
- Average Rating

### 2. CLEAN_Data

The **CLEAN_Data** sheet contains the cleaned transaction-level dataset used for analysis.

It contains **100 transaction records and 22 business fields**.

### 3. RAW_DATA

The **RAW_DATA** sheet contains the original transaction-level data.

### 4. Backend

The **Backend** sheet contains supporting summary calculations used for dashboard analysis.

### 5. Data_Dictionary

The **Data_Dictionary** sheet provides definitions and descriptions for the dataset fields.

### 6. Sheet3

This sheet contains supporting analysis information used within the workbook.

---

## 🧾 Data Dictionary

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

The analysis produces the following major KPIs:

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

**Net Revenue**

`Gross Sales − Discount Amount + Shipping Cost`

**Average Order Value**

`Net Revenue ÷ Total Orders`

---

# 📅 Monthly Performance

| Month | Orders | Net Revenue |
|---|---:|---:|
| January 2026 | 13 | ₹39,980.30 |
| February 2026 | 15 | ₹51,593.55 |
| March 2026 | 14 | ₹49,344.45 |
| April 2026 | 13 | ₹48,113.50 |
| May 2026 | 11 | ₹54,953.45 |
| June 2026 | 13 | ₹54,410.20 |
| July 2026 | 13 | **₹68,669.85** |
| August 2026 | 8 | ₹26,078.30 |

### Monthly Insight

**July 2026** recorded the highest monthly net revenue at **₹68,669.85**.

August contains fewer records in the available analysis period, so its lower revenue should be interpreted in the context of the shorter/latest period.

---

# 🌍 Regional Performance

| Region | Orders | Net Revenue |
|---|---:|---:|
| **West** | 33 | **₹138,824.45** |
| **South** | 28 | **₹112,324.50** |
| East | 21 | ₹79,007.00 |
| North | 18 | ₹62,987.65 |

### Regional Insight

**West** is the leading region, contributing approximately **35.3% of total net revenue**.

West and South together contribute approximately **63.9% of total net revenue**.

This indicates that West and South are important regions for maintaining strong sales, product availability, and fulfilment performance.

---

# 🛍️ Category Performance

| Category | Orders | Net Revenue |
|---|---:|---:|
| **Electronics** | 22 | **₹140,692.10** |
| **Fashion** | 28 | **₹109,891.35** |
| Home & Kitchen | 20 | ₹76,566.25 |
| Sports | 15 | ₹30,347.60 |
| Accessories | 6 | ₹18,810.85 |
| Beauty | 9 | ₹16,835.45 |

### Category Insight

**Electronics** is the highest-revenue category with **₹140,692.10**.

**Fashion** is the second-highest category with **₹109,891.35**.

Together, Electronics and Fashion contribute approximately **63.7% of total net revenue**.

---

# 🏆 Product Performance

| Product | Orders | Net Revenue |
|---|---:|---:|
| **Smart Watch** | 8 | **₹72,413.25** |
| Running Shoes | 12 | ₹69,558.75 |
| Coffee Maker | 11 | ₹62,438.70 |
| Wireless Headphones | 7 | ₹40,074.20 |
| Yoga Mat | 15 | ₹30,347.60 |
| Denim Jeans | 8 | ₹29,721.75 |
| Bluetooth Speaker | 7 | ₹28,204.65 |
| Laptop Backpack | 6 | ₹18,810.85 |
| Water Bottle | 9 | ₹14,127.55 |
| Skincare Kit | 4 | ₹11,029.25 |
| Cotton T-Shirt | 8 | ₹10,610.85 |
| Face Wash | 5 | ₹5,806.20 |

### Product Insight

**Smart Watch** is the highest-revenue product with **₹72,413.25**.

Running Shoes and Coffee Maker are the next strongest products by revenue.

---

# 👥 Customer Segment Analysis

| Customer Segment | Orders | Net Revenue |
|---|---:|---:|
| **Loyal Customer** | 41 | **₹141,179.75** |
| **New Customer** | 34 | ₹138,472.90 |
| **Regular Customer** | 25 | ₹113,490.95 |

### Customer Insight

**Loyal Customers** generate the highest segment revenue at **₹141,179.75**.

**New Customers** also contribute substantial revenue at **₹138,472.90**, creating an opportunity to convert new customers into repeat buyers.

The dataset contains **20 unique customers**, with repeat-order behaviour providing an additional customer-retention opportunity.

---

# 📦 Order Status Analysis

| Order Status | Orders | Share |
|---|---:|---:|
| **Delivered** | 83 | **83%** |
| Pending | 7 | 7% |
| Returned | 6 | 6% |
| Cancelled | 4 | 4% |

### Operational Insight

- **83%** of orders are delivered.
- **7%** of orders are pending.
- **6%** of orders are returned.
- **4%** of orders are cancelled.
- Returned and cancelled orders together represent **10% of total orders**.

Reducing returns, cancellations, and pending orders can improve operational efficiency and customer experience.

---

# 💳 Payment Method Analysis

| Payment Method | Orders | Net Revenue |
|---|---:|---:|
| **Cash on Delivery** | 26 | **₹104,677.30** |
| Debit Card | 22 | ₹91,009.90 |
| UPI | 22 | ₹72,229.15 |
| Credit Card | 13 | ₹68,679.85 |
| Net Banking | 17 | ₹56,547.40 |

### Payment Insight

**Cash on Delivery** generates the highest revenue among the available payment methods, with **₹104,677.30**.

Debit Card is the second-highest payment method by revenue.

---

# 👤 Customer Demographics

## Gender

| Gender | Orders | Net Revenue |
|---|---:|---:|
| Female | 53 | ₹216,666.90 |
| Male | 47 | ₹176,476.70 |

Female customers contribute the larger share of revenue in the available dataset.

## Age

- Minimum age: **21 years**
- Maximum age: **45 years**
- Average age: **approximately 32.7 years**

## Average Rating

**3.98 / 5**

The rating indicates generally positive customer feedback while leaving room for further improvement in customer experience.

---

# 🔎 Key Business Insights

The major findings from the analysis are:

1. **Net revenue is ₹393,143.60** from 100 orders.
2. **Average Order Value is ₹3,931.44**.
3. **West is the leading region**, contributing approximately 35.3% of net revenue.
4. **South is the second-highest region** by revenue.
5. **Electronics is the leading category**, generating ₹140,692.10.
6. **Smart Watch is the leading product**, generating ₹72,413.25.
7. **Loyal Customers generate the highest segment revenue**.
8. New Customers contribute substantial revenue and represent an important retention opportunity.
9. **83% of orders are delivered**.
10. **Returned and cancelled orders represent 10% of total orders**.
11. **Cash on Delivery** has the highest revenue contribution among payment methods.
12. The overall **average rating is 3.98/5**.
13. Total discounts amount to **₹43,649.40**, representing approximately **10.17% of gross sales**.

---

# 💡 Business Recommendations

## 1. Protect High-Performing Regions

Maintain strong product availability, fulfilment, and customer service in **West and South**, while identifying growth opportunities in East and North.

## 2. Focus on High-Performing Categories

Prioritise **Electronics and Fashion** through:

- Targeted promotions
- Product bundles
- Cross-selling
- Upselling
- Personalised campaigns

## 3. Promote High-Value Products

Products such as **Smart Watch, Running Shoes, and Coffee Maker** should receive greater merchandising and promotional attention.

## 4. Improve Customer Retention

Convert new customers into repeat customers through:

- Loyalty programmes
- Second-order offers
- Personalised recommendations
- Post-purchase communication
- Targeted campaigns

## 5. Reduce Returns and Cancellations

Investigate the causes of returned and cancelled orders and improve:

- Product descriptions
- Product quality
- Delivery expectations
- Customer communication
- Fulfilment processes

## 6. Reduce Pending Orders

Monitor pending orders more closely and improve fulfilment speed and customer communication.

## 7. Improve Discount Efficiency

The current discount amount is **₹43,649.40**.

Discounts should be evaluated by:

- Product
- Category
- Customer Segment
- Region
- Order Value

This can help balance sales growth with revenue efficiency.

---

# 📊 Dashboard Features

The Excel dashboard provides an executive-level view of:

### KPI Cards

- Total Orders
- Customers
- Quantity Sold
- Net Revenue
- Average Order Value
- Average Rating

### Analytical Views

- Monthly Revenue
- Monthly Orders
- Regional Performance
- Category Performance
- Product Performance
- Customer Segment Performance
- Order Status
- Payment Method
- Customer Demographics

---

# 🛠️ Tools & Technologies

### Primary Tool

**Microsoft Excel**

### Excel Techniques

- Data cleaning
- Data validation
- Excel tables
- Formulas
- KPI calculations
- Pivot-style summaries
- Charts
- Dashboard development
- Customer segmentation
- Business analysis

---

# 🔄 Project Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Validation
        ↓
CLEAN_Data
        ↓
KPI Calculations
        ↓
Backend / Summary Analysis
        ↓
Dashboard
        ↓
Business Insights
        ↓
Recommendations
