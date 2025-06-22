# Amazon-Dashboard
An interactive Tableau dashboard visualizing Amazon India sales by week, category, region, status, and more.

## 📌 Overview
This dashboard provides a comprehensive visual analysis of Amazon sales performance data. It helps stakeholders understand key metrics such as quantity sold, revenue generated, shipping status, and regional distribution.

## 🔑 Key Features
📅 Time-Series Analysis
Track quantity and revenue by week and category to identify sales trends over time.

📦 Order Status Breakdown
Visualize order progress across multiple stages such as shipped, pending, returned, delivered, and cancelled.

📍 Geographic Insights
Interactive map of India showing state-wise quantity distribution for regional sales performance analysis.

🛍️ Category & Size-Level Insights
Analyze top-performing product categories and sizes in terms of quantity sold.

🚚 Shipping Method Insights
Breakdown of expedited vs. standard shipping across the top 10 Indian states.

📈 Revenue Overview
Total sales revenue filtered by time and category to evaluate business performance.

🧭 B2B vs B2C Analysis
Quick comparison of business-to-business and consumer sales percentages.

🛒 Sales Channel Comparison
Understand the dominance of Amazon vs non-Amazon channels in total sales volume.

📊 Interactive Filters
Dynamic category filter enabling drill-down views across all visualizations.

🎯 High-Level KPIs
Display of essential performance indicators like total quantity, revenue, categories, product sizes, and SKUs.

    
## 📊 Amazon Sales Dashboard

An interactive Tableau dashboard visualizing Amazon India sales by week, category, region, order status, and more.
![Dashboard Preview](https://github.com/thesurya46/Amazon-Dashboard/blob/main/Amazon%20Dashboard%20Image.png)

## 📁 Amazon-Sales-Dashboard

├── 📄Amazon Dashboard image.png    # Screenshot of the Tableau dashboard

├── 📄 Amazon Dashboard.twb    # Tableau dashboard File

├── 📄 README.md                # Project description and documentation

└── 📄 Amazon Sale Report.zip   # Dataset of the Dashboard

## 🛠️ Tools Used

- **Tableau Desktop** – for dashboard creation and data visualization  
- **Excel/CSV** – for dataset handling and preparation  
- **GitHub** – version control and project sharing

 ## ❓ Key Questions
 - Which states contribute the most to total sales?

- What are the most sold product sizes and categories?

-What is the weekly trend in sales and revenue?

-How many orders were cancelled, returned, or shipped?

-What percentage of sales are B2B vs regular?

-Which shipping methods are most commonly used?

## 📚 Dataset
- Source: [https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)

  ## 📊 Dashboard KPIs

The top section of the dashboard displays key performance indicators (KPIs) for a quick overview of Amazon's sales performance during the selected time period:

| KPI Metric             | Value         | Description                                  |
|------------------------|---------------|----------------------------------------------|
| 🧮 **Total Quantity**   | 1,16,649       | Total number of product units sold           |
| 💰 **Total Revenue**    | ₹78,592,678    | Total order value generated in INR           |
| 📦 **Total Products**   | 7,190          | Number of unique product entries             |
| 📐 **Total Sizes**      | 11             | Number of different product sizes available  |
| 🗂️ **Total Categories** | 9              | Number of distinct product categories        |

## 📂 Dataset Information

- **Dataset Name:** Amazon Sales Data (India)
- **Time Period Covered:** March 2022 – June 2022
- **Total Records:** ~1.1 lakh orders
- **File Type:** Excel / CSV
- **Data Size:** ~10 MB

### 🧾 Key Columns

| Column Name          | Description                                                |
|----------------------|------------------------------------------------------------|
| `Order ID`           | Unique identifier for each order                           |
| `Order Date`         | Date the order was placed                                  |
| `Product Category`   | Category of the product (e.g., Clothing, Electronics)      |
| `Size`               | Product size (e.g., S, M, L, XL)                            |
| `Quantity`           | Number of units sold in the order                          |
| `Amount`             | Order value in INR                                         |
| `Shipping Type`      | Expedited or Standard shipping                             |
| `Courier Status`     | Shipped, Delivered, Returned, Cancelled, Pending           |
| `B2B`                | Indicates if the order was a B2B sale                      |
| `Sales Channel`      | Amazon.in or Non-Amazon                                    |
| `Ship-To State`      | Indian state where the order was delivered                 |

## 📊 Visualizations Included

- Weekly Quantity by Category (Line Chart)
- Weekly Revenue by Category (Bar Chart)
- Shipment Status vs Category (Stacked Bar)
- Sales Channel Share (Pie Chart)
- B2B vs Regular Sales (Donut Chart)
- Top 10 Indian States by Quantity (Horizontal Bar)
- Quantity by Size vs Category (Matrix)
- India Map with State-Level Sales (Filled Map)

### 🔄 KPI Behavior

- KPIs are **interactive** and **responsive to filters**:
  - Changing the **date range**, **product category**, or **state filter** will update the values.
  - Helps identify trends in specific segments (e.g., B2B sales, top states, etc.).


### 📌 Use Cases for These KPIs

- **Business Leaders** can quickly assess high-level performance without digging into details.
- **Category Managers** can evaluate which product groups are driving revenue.
- **Supply Chain Teams** can use quantity data to monitor inventory needs.
- **Regional Teams** can correlate state-level quantity with national trends.
  
## 📌 Future Enhancements

- Add category-level drill-through pages
- Include average delivery time analysis
- Integrate customer ratings or returns feedback
- Build mobile-optimized layout for better Tableau Public viewing

## 📫 Contact

Created by **Suryasnata Panigrahi**  
📧 Email: work.suryasnata@gmail.com  
🔁 LinkedIn: [https://www.linkedin.com/in/suryasnata-panigrahi) 



