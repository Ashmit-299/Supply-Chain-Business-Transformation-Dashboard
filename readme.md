### Supply Chain Business Transformation Analytics Dashboard

###### EY-Style Consulting Case Study using SQL, Excel, Power BI and DAX

A professional, interactive Power BI dashboard built to analyze supply chain sales, profitability, order fulfillment, delivery risk, product performance, customer behavior, and business improvement opportunities.

This project is designed as an EY-style consulting case study, where the goal is not only to visualize data but also to identify operational issues and convert insights into actionable business recommendations.

![image alt](https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/8687027e6fe78e1aa7863d7c5284bb06d28061e5/images/Combined%20Look.png)

###### 📌 **Short Description / Purpose**

The **Supply Chain Business Transformation Analytics Dashboard** is an end-to-end Power BI project created to help business leaders monitor supply chain performance across sales, profit, orders, delivery, products, customers, and risk areas.

The dashboard focuses on identifying key business problems such as high late delivery rate, low-profit products, cancellation exposure, uneven regional performance, and operational risk. It converts raw supply chain data into interactive visuals and consulting-style recommendations for better decision-making.

\# Intended Users

This dashboard is designed for:

\- Supply Chain Managers

\- Business Analysts

\- Operations Teams

\- Consulting Analysts

\- Product and Category Managers

\- Regional Business Leaders

\- Data Analytics Portfolio Reviewers



###### 🛠️ **Tech Stack**

The dashboard was built using the following tools and technologies:

\- 📊 **Power BI Desktop –** Used for dashboard design, data modeling, DAX measures, and interactive reporting.

\- 📂 **Power Query –** Used for data cleaning, transformation, column formatting, and helper column creation.

\- 🧠 **DAX –** Used for KPI measures, year-over-year comparison, delivery risk calculations, profit metrics, and conditional formatting.

\- 📝 **Data Modeling –** Star schema model created using fact and dimension tables.

\- 📁 **CSV / Excel –** Used for initial dataset review and cleaning.

\- 🧩 **Custom Visual Design –** Used shapes, icons, cards, slicers, maps, bar charts, donut charts, matrix visuals, and navigation buttons.

\- 🌐 **GitHub –** Used for project documentation and portfolio presentation.



###### 📂 **Data Source**

Dataset Used

**DataCo Supply Chain Dataset**

The dataset was downloaded from Kaggle and used as a replacement for an MNC-style supply chain business case. The data contains order, customer, product, sales, profit, delivery, market, and shipping-related information.



\# Dataset Details

\- **Source Platform:** Kaggle

\- **Dataset Name:** DataCo Supply Chain Dataset

\- **Main File Used:** DataCoSupplyChainDataset.csv

\- **Records:** Approximately 180,000+ rows

\- **Data Type:** Supply chain transaction/order-item level data



\# Main Columns Used

The dataset includes columns related to:

\- Order ID

\- Order Date

\- Shipping Date

\- Order Status

\- Customer ID

\- Customer Segment

\- Market

\- Region

\- Country

\- Product Name

\- Category Name

\- Department Name

\- Sales

\- Profit

\- Order Quantity

\- Shipping Mode

\- Actual Shipping Days

\- Scheduled Shipping Days

\- Late Delivery Risk



###### 🧹 **Data Cleaning \& Preparation**

The original dataset was cleaned and prepared before dashboard development.



\# Cleaning Steps Performed

\- Removed unnecessary and sensitive columns.

\- Removed columns with no analytical value.

\- Renamed columns into clean, readable naming format.

\- Changed incorrect data types.

\- Converted date fields into proper date/date-time format.

\- Created helper columns for delivery performance and profit status.

\- Cleaned country values, including converting inconsistent country names.

\- Created a star schema model with fact and dimension tables.

\- Built a dedicated date table for time-based analysis.

\- Created DAX measures for KPIs, trends, risk metrics, and year-over-year comparison.



###### 🧱 **Data Model**

The dashboard uses a star schema data model.

\- **fact\_orders –** Main transaction table containing order, sales, profit, delivery, and status metrics.

\- **dim\_customer –** Customer-related details such as customer ID, segment, city, state, and country.

\- **dim\_product –** Product, category, department, and price information.

\- **dim\_location –** Market, region, country, state, and city information.

\- **dim\_shipping –** Shipping mode, delivery status, and delivery performance fields.

\- **dim\_date –** Date table used for monthly trend and year-over-year calculations.



\# Model Purpose

The model was designed to support:

\- Fast filtering

\- Clean relationships

\- Reusable DAX measures

\- Page-level slicers

\- Cross-report interactions

\- Time intelligence calculations



###### ❓ **Business Problem**

A global supply chain company is facing operational and profitability challenges across multiple regions and markets.

The major business issues include:

\- High late delivery rate

\- Delivery risk across shipping modes

\- Low-profit orders and categories

\- Uneven regional sales and profitability

\- Order cancellation exposure

\- Product-level margin issues

\- Market-level operational risk

Business leaders need a single interactive dashboard to monitor these issues and identify where improvement actions are required.



###### 🎯 **Goal of the Dashboard**

The goal of this dashboard is to provide a consulting-style analytics solution that helps leadership:

\- Track overall business performance

\- Monitor sales, profit, and order trends

\- Identify high-risk delivery regions

\- Analyze product and category profitability

\- Understand customer and market behavior

\- Detect low-profit and cancellation risks

\- Convert insights into business recommendations



📊 **Dashboard Pages**

The Power BI report contains the following pages:

**1. Executive Overview**

**2. Sales Analytics**

**3. Order Analytics**

**4. Delivery Analytics**

**5. Product Analytics**

**6. Customer Analytics**

**7. Risk \& Insights**

**8. Business Recommendations \& Key Insights**



📌 **Dashboard Features / Highlights**

1\. Executive Overview

The Executive Overview page provides a high-level snapshot of business performance.

Key metrics include:

\- Total Sales

\- Total Profit

\- Total Orders

\- Average Delivery Days

\- Late Delivery Rate

\- Total Customers

Key visuals include:

\- Monthly sales trend

\- Sales by shipping mode

\- Sales by market

\- Profit by region

\- Orders by status

\- Top products by sales

This page helps executives quickly understand overall business health.



2\. Sales Analytics

The Sales Analytics page analyzes revenue and profitability performance.

Key metrics include:

\- Total Sales

\- Total Profit

\- Profit Margin %

\- Average Order Value

\- Total Orders

Key visuals include:

\- Sales trend by month

\- Sales by market

\- Sales by region

\- Sales by category

\- Top products by sales

\- Top products by profit

This page helps identify where sales are coming from and whether revenue is profitable.



3\. Order Analytics

The Order Analytics page focuses on order volume, order status, cancellation, and fulfillment patterns.

Key metrics include:

\- Total Orders

\- Complete Orders

\- Canceled Orders

\- Pending Payment Orders

\- Processing Orders

\- Canceled Order Rate %

Key visuals include:

\- Monthly order trend

\- Orders by region

\- Orders by market

\- Orders by shipping mode

\- Orders by status

\- Top countries by orders

This page helps business teams monitor order flow and fulfillment issues.



4\. Delivery Analytics

The Delivery Analytics page analyzes supply chain delivery performance.

Key metrics include:

\- Average Delivery Days

\- On-Time Delivery Rate %

\- Late Delivery Rate %

\- Late Risk Orders

\- Average Scheduled Shipping Days

\- Average Delay Days

Key visuals include:

\- Average delivery days trend

\- Late delivery rate by region

\- Late delivery rate by market

\- Delivery performance status

\- Orders by shipping mode

\- Average delivery days by shipping mode

This page helps identify delivery delays, late delivery risk, and weak logistics areas.



5\. Product Analytics

The Product Analytics page focuses on product, category, and department-level performance.

Key metrics include:

\- Total Products

\- Total Categories

\- Total Departments

\- Total Quantity Sold

\- Average Product Price

\- Low Profit Order Rate %

Key visuals include:

\- Top categories by sales

\- Top categories by profit

\- Top departments by sales

\- Low-profit products table

\- Treemap of product sales

\- Top products by sales

This page helps identify profitable products, weak products, and category-level opportunities.



6\. Customer Analytics

The Customer Analytics page analyzes customer behavior and demand patterns.

Key metrics include:

\- Total Customers

\- Total Sales

\- Average Revenue per Customer

\- Average Orders per Customer

\- High Value Customers

\- Total Orders

Key visuals include:

\- Profit by customer segment

\- Customer order frequency

\- Top customers by sales

\- Top countries by sales

\- Sales by customer segment

This page helps understand customer value, customer segments, and regional demand patterns.



7\. Risk \& Insights

The Risk \& Insights page focuses on operational risk and business problem areas.

Key metrics include:

\- Late Delivery Rate

\- Late Risk Orders

\- Canceled Orders

\- Canceled Rate

\- Low Profit Orders

\- Low Profit Order Rate

Key visuals include:

\- Risk by shipping mode

\- Overall risk by market

\- Risk by region

\- Delivery risk status

\- Low profit risk by category

\- Risk detail matrix

This page acts as the diagnostic layer of the dashboard, helping users identify where the business is exposed to risk.



8\. Business Recommendations \& Key Insights

The final page converts dashboard insights into consulting-style recommendations.

Recommendation areas include:

\- Improve delivery performance

\- Optimize shipping mode strategy

\- Reduce low-profit orders

\- Focus on profitable categories

\- Reduce order cancellation risk

\- Improve regional performance

The page also highlights expected business impact in areas such as:

\- Revenue uplift

\- Profit improvement

\- Delivery performance

\- Operational efficiency

\- Customer satisfaction



###### 📈 **Key Business Insights**

Some of the major insights identified from the dashboard include:

\- Late delivery risk is a major operational issue across multiple regions and markets.

\- Certain shipping modes show higher delay exposure and require performance monitoring.

\- Low-profit orders significantly affect overall business profitability.

\- Some categories generate strong sales but require margin review.

\- Regional performance varies across sales, delivery risk, and profitability.

\- Customer segments show different revenue and profit contribution patterns.

\- Risk monitoring should be used to support operational and strategic decisions.



###### 💼 **Business Impact**

The dashboard can help business teams in the following ways:

1.\\ Delivery Optimization

Helps identify late delivery patterns by region, market, and shipping mode.

2\. Profitability Improvement

Highlights low-profit products, categories, and order patterns.

3\. Operational Risk Control

Tracks cancellation, delivery risk, and low-margin exposure.

4\. Regional Strategy

Supports region-wise performance comparison and market-specific decisions.

5\. Product Strategy

Helps identify high-performing categories and weak-margin products.

6\. Customer Understanding

Provides visibility into customer value, segments, and order frequency.



###### 🧮 **Key DAX Measures**

Some of the important DAX measures used in the dashboard include:

**DAX**

Total Sales = SUM(fact\_orders\[sales])

Total Profit = SUM(fact\_orders\[order\_profit\_per\_order])

Total Orders = DISTINCTCOUNT(fact\_orders\[order\_id])

Total Customers = DISTINCTCOUNT(fact\_orders\[customer\_id])

Profit Margin % = DIVIDE(\[Total Profit], \[Total Sales], 0)

Average Order Value = DIVIDE(\[Total Sales], \[Total Orders], 0)

Average Delivery Days = AVERAGE(fact\_orders\[actual\_shipping\_days])

Late Delivery Rate % = DIVIDE(\[Late Risk Orders], \[Total Orders], 0)

Low Profit Order Rate % = DIVIDE(\[Low Profit Orders], \[Total Orders], 0)

Canceled Order Rate % = DIVIDE(\[Canceled Orders], \[Total Orders], 0)



###### 📷 **Screenshots / Dashboard Preview**

Executive Overview
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Executive%20Overview.png))

Sales Analytics
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Sales%20Analytics.png))

Order Analytics
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Order%20Analytics.png))

Delivery Analytics
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Delivery%20Analytics.png))

Product Analytics
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Product%20Analytics.png))

Customer Analytics
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Customer%20Analytics.png))

Risk \& Insights
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Risk%20%26%20Insights.png))

Business Recommendations
![image alt]((https://github.com/Ashmit-299/Supply-Chain-Business-Transformation-Dashboard/blob/91a5dbd3d4fbeb7ea1336cc51d1649a50185af6e/images/Recommendation.png))


###### 📁 **Project Structure**

Supply-Chain-Business-Transformation-Dashboard/

│

├── README.md

├── dashboard/

│   └── Supply\_Chain\_Business\_Transformation\_Dashboard.pbix

│

├── data/

│   ├── supply\_chain\_data\_final.csv

│   └── data\_dictionary.csv

│

├── images/

│   ├── executive\_overview.png

│   ├── sales\_analytics.png

│   ├── order\_analytics.png

│   ├── delivery\_analytics.png

│   ├── product\_analytics.png

│   ├── customer\_analytics.png

│   ├── risk\_insights.png

│   └── recommendations.png

│

└── assets/
    └── icons/





###### 🚀 **How to Use**

Download the .pbix file from the dashboard/ folder.

Open the file using Power BI Desktop.

Use the slicers to filter by date range, market, region, and shipping mode.

Navigate between report pages using the left sidebar.

Review business insights and recommendations from the final pages.



###### 🔍 **Key Learnings**

While building this project, I learned how to:

Clean and prepare supply chain data using Power Query.

Build a star schema data model in Power BI.

Create DAX measures for sales, profit, orders, delivery, and risk KPIs.

Design a professional dark-themed consulting dashboard.

Build interactive page navigation using sidebar buttons.

Apply conditional formatting for KPI indicators and risk matrices.

Convert dashboard insights into business recommendations.



###### 📌 **Project Outcome**

This project demonstrates the ability to build a complete business intelligence solution using Power BI. It combines data cleaning, modeling, DAX calculations, visual storytelling, risk analysis, and consulting-style recommendations.

The dashboard helps stakeholders monitor supply chain performance and identify improvement areas across sales, delivery, products, customers, and operational risk.



###### 👤 **Author**

Ashmit Pandey

GitHub: https://github.com/Ashmit-299

LinkedIn: www.linkedin.com/in/ashmit-pandey-269675357

Email: pandeyashmit299@gmail.com

