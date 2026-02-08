# Coffee Shop Sales Performance & Operational Analytics

### 1. Sales & Footfall Performance Analytics

A comprehensive Excel-based data analytics project designed to transform raw coffee shop transaction data into a dynamic executive dashboard. The project focuses on identifying peak operational hours, product category performance, and customer purchasing patterns to optimize daily business operations.

### 2. Purpose

The purpose of this dashboard is to provide coffee shop owners and managers with a clear view of store health and peak traffic times. By analyzing KPIs like **Total Sales**, **Footfall**, and **Average Order Value**, stakeholders can make data-driven decisions regarding staff scheduling during peak hours, inventory management for top-selling categories, and product pricing strategies.

### 3. Tech Stack

* **📊 MS Excel (Advanced)** – Used as the primary tool for data visualization and dashboard construction.
* **📂 Power Query (ETL)** – Utilized for cleaning raw CSV data, extracting time components (hours/days), and handling inconsistent product detail formats.
* **🧠 Power Pivot & DAX** – Implementation of a data model to handle large datasets efficiently and creation of custom measures (Average Bill per Person, Transaction Count).
* **🎨 UI/UX Design** – Integration of a coffee-themed color palette with rounded-edge containers and custom icons for a professional, cohesive brand aesthetic.

### 4. Data Source

The project utilizes a Coffee Shop Sales dataset containing:

* **Transaction Details:** Transaction ID, Date, and 24-hour Time stamps.
* **Product Hierarchy:** Product Category (Coffee, Tea, Bakery, etc.), Product Type, and Detailed Descriptions.
* **Sales Metrics:** Transaction Quantity, Unit Price, and Calculated Total Bill.
* **Store Geography:** Specific store locations (e.g., Hell's Kitchen, Astoria, Lower Manhattan).

### 5. Features

**Business Problem:**
Retail managers often struggle to identify exactly when "rush hour" occurs and which products are driving the most revenue versus those just moving high volume. Key questions addressed include:

* At what specific hour does footfall peak across different locations?
* Which product categories (e.g., Coffee vs. Tea) contribute most to the total revenue?
* Does customer behavior change significantly between weekdays and weekends?

**Goal of the Dashboard:**
To provide a 360-degree operational view that enables:

* **Temporal Analysis:** Visualizing sales trends by the hour to optimize staffing levels.
* **Dynamic Filtering:** Integrated slicers for "Month" and "Day of Week" that update the entire dashboard instantly.
* **Product Deep-Dives:** Identifying top 5 selling products and size preferences (Large vs. Regular).

**Walkthrough of Key Visuals:**

* **KPI Scorecards (Top Ribbon):** Four high-level metrics showing Total Sales, Total Footfall, Average Bill per Person, and Average Order Quantity.
* **Hourly Sales Trend (Line Chart):** A "heartbeat" chart showing transaction peaks, highlighting the 8:00 AM – 10:00 AM surge.
* **Category Distribution (Pie Chart):** A percentage breakdown showing the dominance of Coffee and Tea in the revenue mix.
* **Location Comparison (Grouped Bar Chart):** A side-by-side view of Footfall vs. Sales across different shop locations.
* **Weekly Heatmap (Bar Chart):** A breakdown of sales by day of the week to identify the "weekend dip" or "weekday rush."

### 6. Business Impact & Insights

* **Staffing Optimization:** Identifying peak hours allows for better shift allocation, reducing wait times during morning rushes.
* **Menu Engineering:** Recognizing that "Large" sizes dominate certain categories can lead to targeted upselling strategies.
* **Location Strategy:** Pinpointing high-footfall but low-margin locations helps in refining regional pricing or discount structures.

### 7. Screenshot:
![Dashboard Preview](https://github.com/chinmai-budati/Coffee-Shop-Sales-Dashboard/blob/main/Coffee%20Shop%20Sales%20Dashboard.png)
