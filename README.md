# E-Commerce-Order-Customer-Analytics
README / Project Documentation
1. Project Overview

E-Commerce Order & Customer Analytics is an Excel-based business intelligence project designed to analyse e-commerce order transactions, customer behaviour, product performance, regional sales, payment methods, and order outcomes.

The project converts transaction-level data into meaningful KPIs, summaries, trends, comparisons, and business recommendations to support data-driven decision-making.

2. Project Objectives

The main objectives of this project are:

Analyse overall e-commerce order and revenue performance.
Measure key business KPIs such as Net Revenue, Orders, Customers, Quantity Sold, Average Order Value, and Average Rating.
Identify high-performing regions, categories, and products.
Analyse customer behaviour using Customer Segments, Gender, Age, and repeat-order patterns.
Evaluate order performance based on Delivered, Returned, Cancelled, and Pending statuses.
Analyse revenue and order contribution by Payment Method.
Identify important business opportunities and operational issues.
Present the findings through an interactive and management-friendly Excel dashboard.
3. Dataset Information

The project uses the Excel workbook:

E_Commerce_Order_Customer_Analytics_Dataset_ (4).xlsx

Analysis Period

4 January 2026 – 20 August 2026

Dataset Size
Metric	Value
Transaction Records	100
Unique Orders	100
Unique Customers	20
Quantity Sold	257
Data Columns	22
4. Workbook Structure

The Excel workbook contains the following sheets:

4.1 Dashboard

The Dashboard sheet provides the main executive-level view of the project.

It presents important KPIs including:

Net Revenue
Total Orders
Customers
Quantity Sold
Average Order Value
Average Rating

The dashboard is designed to provide a quick overview of overall e-commerce performance.

4.2 CLEAN_Data

The CLEAN_Data sheet contains the cleaned transaction-level dataset used for analysis.

It contains 100 records and 22 columns.

4.3 RAW_DATA

The RAW_DATA sheet contains the raw transaction-level information used as the source dataset.

4.4 Backend

The Backend sheet contains supporting summary/pivot-style calculations used for dashboard analysis.

4.5 Data_Dictionary

The Data_Dictionary sheet explains the meaning of the columns used in the dataset.

4.6 Sheet3

This sheet contains supporting summary information generated during the analysis.

5. Data Dictionary
Column	Meaning
Order ID	Unique order number
Order Date	Date of order
Customer ID	Unique customer number
Customer Name	Customer name
Gender	Customer gender
Age	Customer age
City	Customer city
State	Customer state
Region	Geographical region
Product	Purchased product
Category	Product category
Quantity	Number of units purchased
Unit Price	Price per unit
Discount	Discount percentage
Shipping Cost	Shipping charge
Payment Method	Payment method used
Order Status	Current order status
Rating	Customer rating
Customer Segment	Customer type/segment
Gross Sales	Quantity × Unit Price
Discount Amount	Gross Sales × Discount
Net Revenue	Gross Sales − Discount Amount + Shipping Cost
6. Key Business KPIs

The analysis of the updated dataset produces the following results:

KPI	Result
Gross Sales	₹429,243.00
Discount Amount	₹43,649.40
Shipping Cost	₹7,550.00
Net Revenue	₹393,143.60
Total Orders	100
Customers	20
Quantity Sold	257
Average Order Value	₹3,931.44
Average Rating	3.98 / 5
Discount Rate	10.17%
Key Formula

Net Revenue = Gross Sales − Discount Amount + Shipping Cost

Average Order Value = Net Revenue ÷ Total Orders

7. Monthly Performance
Month	Orders	Net Revenue
January	13	₹39,980.30
February	15	₹51,593.55
March	14	₹49,344.45
April	13	₹48,113.50
May	11	₹54,953.45
June	13	₹54,410.20
July	13	₹68,669.85
August	8	₹26,078.30
Monthly Insight

July 2026 recorded the highest monthly net revenue at ₹68,669.85.

August has only 8 orders in the available dataset, so its lower revenue should be interpreted in the context of the shorter/latest-period coverage.

8. Regional Performance
Region	Orders	Net Revenue
West	33	₹138,824.45
South	28	₹112,324.50
East	21	₹79,007.00
North	18	₹62,987.65
Regional Insight

West is the strongest region, generating approximately 35.3% of total net revenue.

West and South together generate approximately 63.9% of total net revenue, making these regions important areas for maintaining strong sales and fulfilment performance.

9. Category Performance
Category	Orders	Net Revenue
Electronics	22	₹140,692.10
Fashion	28	₹109,891.35
Home & Kitchen	20	₹76,566.25
Sports	15	₹30,347.60
Accessories	6	₹18,810.85
Beauty	9	₹16,835.45
Category Insight

Electronics is the highest-revenue category with ₹140,692.10.

Fashion is the second-highest category with ₹109,891.35.

Together, Electronics and Fashion contribute approximately 63.7% of total net revenue.

10. Product Performance
Product	Orders	Net Revenue
Smart Watch	8	₹72,413.25
Running Shoes	12	₹69,558.75
Coffee Maker	11	₹62,438.70
Wireless Headphones	7	₹40,074.20
Yoga Mat	15	₹30,347.60
Denim Jeans	8	₹29,721.75
Bluetooth Speaker	7	₹28,204.65
Laptop Backpack	6	₹18,810.85
Water Bottle	9	₹14,127.55
Skincare Kit	4	₹11,029.25
Cotton T-Shirt	8	₹10,610.85
Face Wash	5	₹5,806.20
Product Insight

Smart Watch is the highest-revenue product with ₹72,413.25.

Running Shoes and Coffee Maker are the next strongest products by revenue.

11. Customer Segment Analysis
Customer Segment	Orders	Net Revenue
Loyal Customer	41	₹141,179.75
New Customer	34	₹138,472.90
Regular Customer	25	₹113,490.95
Customer Insight

Loyal customers generate the highest revenue at ₹141,179.75.

New customers are also a major revenue contributor at ₹138,472.90, indicating an opportunity to convert new customers into repeat buyers.

The dataset contains 20 unique customers, and repeat-order analysis shows that a meaningful portion of customers have placed multiple orders.

12. Order Status Analysis
Order Status	Orders	Revenue
Delivered	83	₹316,616.15
Pending	7	₹31,766.45
Returned	6	₹30,602.45
Cancelled	4	₹14,158.55
Operational Insight
83% of orders are delivered.
7% are pending.
6% are returned.
4% are cancelled.
Returned + cancelled orders represent 10% of all orders.

Returns and cancellations therefore represent an important area for operational improvement.

13. Payment Method Analysis
Payment Method	Orders	Net Revenue
Cash on Delivery	26	₹104,677.30
Debit Card	22	₹91,009.90
UPI	22	₹72,229.15
Credit Card	13	₹68,679.85
Net Banking	17	₹56,547.40
Payment Insight

Cash on Delivery has the highest revenue contribution at ₹104,677.30.

Debit Card is the second-highest payment method by revenue.

14. Customer Demographics
Gender
Gender	Orders	Net Revenue
Female	53	₹216,666.90
Male	47	₹176,476.70

Female customers contribute the larger share of revenue in the available dataset.

Age
Minimum customer age: 21 years
Maximum customer age: 45 years
Average customer age: approximately 32.7 years
Average Rating

3.98 / 5

The rating indicates generally positive customer feedback, while still leaving room for improvement in customer experience.

15. Major Business Insights

The analysis produces the following major findings:

Net revenue is ₹393,143.60 from 100 orders.
Average Order Value is ₹3,931.44.
West is the leading region, contributing approximately 35.3% of net revenue.
South is the second-largest region by revenue.
Electronics is the leading category, generating ₹140,692.10.
Smart Watch is the highest-revenue product, generating ₹72,413.25.
Loyal customers generate the highest segment revenue.
New customers also contribute a substantial amount of revenue, creating a strong retention opportunity.
83% of orders are delivered.
10% of orders are returned or cancelled, highlighting an operational improvement opportunity.
Cash on Delivery generates the highest payment-method revenue.
The overall average rating is 3.98/5.
Discounts total ₹43,649.40, representing approximately 10.17% of gross sales.
16. Recommendations
1. Protect High-Performing Regions

Maintain strong product availability, fulfilment, and customer service in West and South, while identifying growth opportunities in East and North.

2. Focus on High-Performing Categories

Prioritise Electronics and Fashion through:

Product promotions
Bundling
Cross-selling
Upselling
Targeted campaigns
3. Promote High-Value Products

Products such as Smart Watch, Running Shoes, and Coffee Maker should receive greater merchandising and promotional attention.

4. Improve Customer Retention

Convert new customers into repeat customers through:

Loyalty programmes
Second-order offers
Personalised recommendations
Post-purchase communication
Targeted promotional campaigns
5. Reduce Returns and Cancellations

Analyse the reasons behind returned and cancelled orders and improve:

Product descriptions
Product quality
Delivery expectations
Customer communication
Order fulfilment
6. Reduce Pending Orders

Monitor pending orders more closely and introduce faster fulfilment and customer communication processes.

7. Improve Discount Efficiency

The current discount amount is ₹43,649.40.

Discounts should be evaluated by:

Product
Category
Customer segment
Order value
Region

This can help ensure that discounts generate incremental sales rather than unnecessarily reducing revenue.

17. Dashboard Components

The Excel dashboard is designed around the following components:

KPI Cards
Total Orders
Customers
Quantity Sold
Net Revenue
Average Order Value
Average Rating
Analytical Views
Monthly Revenue
Regional Performance
Category Performance
Product Performance
Customer Segment Performance
Order Status
Payment Method
Customer Demographics
Management Insights

The dashboard converts transaction-level information into a concise management view that can be used to identify:

Revenue leaders
Growth opportunities
Customer opportunities
Operational issues
Product priorities
18. Tools & Technologies
Primary Tool

Microsoft Excel

Excel Features Used / Supported
Data cleaning
Excel tables
Formulas
Pivot-style summaries
KPI calculations
Charts
Dashboard design
Data categorisation
Customer segmentation
Conditional analysis
Data dictionary
19. Project Workflow
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
20. Project Outcome

This project provides a complete E-Commerce Order & Customer Analytics solution that transforms 100 transaction records into an executive-level business intelligence dashboard.

The analysis enables management to understand:

How much revenue is being generated
Which regions perform best
Which categories and products generate the most revenue
Which customer segments contribute most
How customers are purchasing
How many orders are delivered, returned, cancelled, or pending
Where customer retention opportunities exist
Where operational improvements are required
21. Future Scope

The project can be further enhanced by adding:

Customer Lifetime Value (CLV)
Cohort analysis
Customer retention rate
Customer acquisition analysis
Profit margin analysis
Product profitability
Regional profitability
Revenue forecasting
Demand forecasting
Automated dashboard refresh
Power BI integration
Interactive slicers and drill-down reporting
Automated monthly management reports
22. Conclusion

The E-Commerce Order & Customer Analytics project demonstrates how transaction-level e-commerce data can be converted into meaningful business intelligence using Microsoft Excel.

With 100 orders, 20 customers, 257 units, and ₹393,143.60 in net revenue, the dataset provides sufficient information to evaluate commercial performance, customer behaviour, regional contribution, product performance, payment patterns, and operational outcomes.

The analysis identifies West as the leading region, Electronics as the leading category, Smart Watch as the leading product, and Loyal Customers as the highest-revenue customer segment.

The dashboard therefore provides a practical foundation for data-driven sales, marketing, customer-retention, and operational decisions.

23. Author

Project Title: E-Commerce Order & Customer Analytics
Presented by: Soumya Roy
Project Type: Excel Business Intelligence / Data Analytics Project
Analysis Period: January–August 2026
Primary Tool: Microsoft Excel
