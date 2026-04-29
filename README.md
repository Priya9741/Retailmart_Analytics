# RetailMart V2 Analytics Dashboard (SQL)

## Overview
  The RetailMart V2 Analytics Dashboard is an advanced, data-driven analytics system built using SQL to analyze retail business performance across multiple domains.
It processes structured datasets, performs complex queries, and presents insights through modular dashboards such as Executive, Sales, Customer, Marketing, Operations, Finance, Audit, and Supply Chain.
This project solves key business problems and enables data-driven decision-making at an enterprise level.

## 🗂️ Datasets Used

## 1. Orders Table
           Contains transaction-level data including:
  Order ID, Sales, Profit, Discount
  Customer Name, Segment
  Order Date, Shipping Details
  Market, Country

## 2. Returns Table
  Tracks returned orders:
  Order ID
  Return Status
  Market

## 3. Customers / Products / Stores Tables
  Used for:
  Customer segmentation
  Product performance analysis
  Store-level insights

## 4. Operations / Finance / Audit / Supply Chain Tables
  Contain data related to:
  Logistics & delivery
  Payroll & expenses
  API/system logs
  Inventory & production
  
---

## 📊 Problem Statements Solved with SQL
## 1. Executive KPIs Dashboard
Objective:
Calculate and display key business KPIs such as revenue, orders, customers, and profit.
**Steps:**
  Use SQL aggregations:
      SUM(Sales) → Total Revenue
      SUM(Profit) → Total Profit
      COUNT(Order_ID) → Total Orders
  Create time-based grouping using:
      GROUP BY YEAR(Order_Date), MONTH(Order_Date)
  Identify:
       Top customers
       Top products

## 2. Sales Analysis
Objective:
Analyze sales trends and performance.
** Steps: **
   Query daily and monthly sales using GROUP BY
   Analyze sales by:
      Region
      Payment method
      Category
   Calculate growth trends over time

## 3. Customer Analytics
Objective:
Understand customer behavior and segmentation.
** Steps: **
   Perform RFM analysis using SQL
   Calculate:
      Customer Lifetime Value (CLV)
  Identify:
      High-value customers
      Churn-risk customers

## 4. Product Analytics
Objective:
Evaluate product performance.
** Steps:**
Aggregate sales by product and category
Perform ABC analysis using ranking functions
Identify:
Top-performing products
Low-performing products

## 5. Store Analytics
Objective:
Compare store and regional performance.
** Steps: **
Group sales by store and region
Rank stores using RANK() or DENSE_RANK()
Calculate store-level KPIs

## 6. Operations Analytics
Objective:
Analyze logistics and delivery performance.
**Steps:**
Calculate:
Delivery SLA %
Average delivery time
Return rate
Aggregate support data:
Open tickets
Refund amounts
Key Metrics:
Delivery SLA: 43.6%
Avg Delivery Time: 4 days
Return Rate: 9%
Refunds: ₹12.81 Cr

## 7. Marketing Analytics
Objective:
Evaluate campaign performance and user engagement.
**Steps:**
Calculate Campaign ROI using revenue vs spend
Analyze:
Platform-wise spend
Email engagement metrics
Perform funnel analysis:
Visit → Cart → Purchase

## 8. Finance & HR Analytics
Objective:
Analyze financial performance and workforce costs.
** Steps: **
Calculate:
Monthly P&L using aggregated revenue & expenses
Analyze payroll:
By department
By role
Compute:
Average salary
Total payroll contribution

## 9. Audit & System Monitoring
Objective:
Monitor system performance and detect anomalies.
** Steps: **
Calculate:
Error rate (%)
API response time
Analyze API logs:
Requests
Failures
Detect suspicious activity:
Off-hours system changes
Key Metrics:
Error Rate: 51.7%
Avg Response Time: 1049 ms
System Health: Critical

## 10. Supply Chain Analytics
Objective:
Optimize production, inventory, and supplier performance.
** Steps:**
Track:
Units produced
Reject rates
Analyze:
Warehouse inventory
Supplier reliability
Identify quality issues using rejection data
Key Metrics:
Warehouses: 5
Suppliers: 91
Units Produced: 2.5 Cr+
Reject Rate: 2.5%

## Dynamic Features
The SQL-based system includes:
Complex joins across multiple tables
Aggregations and window functions
Real-time KPI calculations
Multi-domain analytics
Scalable query design

---

## Next Steps for Extension
Predictive analytics (sales forecasting)
Customer churn prediction
      Real-time dashboard integration (Power BI/Tableau)
       Automated anomaly detection



## Significance
This project helps businesses to:
   Track performance across departments
   Identify inefficiencies in operations
   Optimize marketing and supply chain
   Improve customer experience
   Ensure system reliability and security



## Visuals
This repository includes:
Dashboard screenshots for all modules
KPI summaries
SQL query outputs
