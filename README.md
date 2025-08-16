# Amazon_Sales_Analytics_Dashboard

📊 Amazon Sales Analytics Dashboard
The **Amazon Sales Analytics Dashboard** is an end-to-end **Business Intelligence (BI) solution** built using **Power BI** to monitor and analyze **sales, inventory, transportation, and delivery performance**.
This project transforms raw Amazon sales data into **actionable insights** for business owners, managers, and analysts. It provides visibility into key business areas like **sales trends, stock management, courier performance, and customer payment behaviors**, helping stakeholders make **data-driven decisions**.

🌟 Features

### 🔹 Sales & Revenue
    * Track **overall sales** and **orders** over time
    * Breakdown by **city, state, and product category**
    * Identify **top-performing products and regions**
### 🔹 Inventory Management
    * Monitor **stock levels by product and brand**
    * Track **fulfilled vs. unfulfilled orders**
    * Identify **fast-moving and low-stock products**
### 🔹 Logistics & Transportation
    * Analyze **shipping costs** across courier services
    * Evaluate performance of couriers (Blu Dart, Delhivery, India Post, etc.)
    * Understand distribution by **transportation mode** (Air, Rail, Road)
### 🔹 Order & Delivery Insights
    * Order status tracking (Delivered, Shipped, Cancelled)
    * Revenue analysis by **payment method** (UPI, Cards, COD, Net Banking)
    * Regional delivery performance across major cities



## ⚙️ How to Build This Project 
1️⃣ **Prepare the Dataset**
* Collect raw sales & logistics data in CSV/Excel format
* Ensure consistent formatting of dates, numbers, and categories

2️⃣ **Load Data into Power BI**
* Import multiple datasets
* Use Power Query for cleaning & transformation

3️⃣ **Create Data Model**
* Define relationships between tables (Orders ↔ Products ↔ Couriers)
* Build a star schema for optimized queries

4️⃣ **Write DAX Measures**
Examples:
Total Sales = SUM(Sales[Amount])
Total Orders = COUNTROWS(Orders)
Average Shipping Cost = AVERAGE(Shipping[Cost])
Revenue by Payment Method = CALCULATE(SUM(Payments[Amount]), Payments[Method] = "UPI")

5️⃣ **Design Dashboards**
* **Overview:** KPIs + Sales trends
* **Sales:** Orders, stock value, product performance
* **Inventory:** Stock left, fulfillment status, brand insights
* **Transportation:** Courier costs, delivery modes, performance
* **Order & Delivery:** Payment methods, delivery regions, order trends

6️⃣ **Deploy & Share**
* Save as `.pbix` file
* Publish on Power BI Service for online access
* Export snapshots for reporting (PDF/PNG)

