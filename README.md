# Adventure Works Power BI Dashboard

This repository contains my Power BI project analyzing the Adventure Works dataset. The goal of this project was to derive meaningful insights into sales performance, customer behavior, and product trends, while creating a visually engaging and interactive dashboard.

---

## Project Overview

The project involved the following key steps:

1. **Data Cleaning and Preparation:**
   - Cleaned and transformed data using Power Query.
   - Handled missing values, standardized data formats, and ensured data accuracy.

2. **Data Modeling:**
   - Built a relationship model using a star schema.
   - Connected fact tables (Sales and Returns) with dimension tables (Customers, Products, Calendar, etc.) for efficient analysis.

3. **Dashboard Design:**
   - Designed an interactive dashboard with multiple pages to answer business questions and support decision-making.

---

## Dashboard Features

### 1. **Overview Page**
   - **KPIs:** Showcased key metrics like Total Revenue, Total Profit, Orders, and Return Rate.
   - **Visuals:**
     - Line Chart: Displayed revenue trends over time.
     - Bar Chart: Highlighted top-performing product categories.
     - Matrix Table: Listed top 10 products by revenue, orders, and returns.

### 2. **Geographic Insights Page**
   - **Map Visualization:**
     - Displayed sales and profit data across regions (Europe, North America, Pacific).
     - Used circle sizes to represent sales volume and profitability intensity.

### 3. **Product Detail Page**
   - **Filters and Slicers:** Enabled filtering by year, product, and price.
   - **Visuals:**
     - Gauge Charts: Compared monthly revenue, orders, and profit against targets.
     - Line and Area Charts: Displayed product performance over time.
     - Report Summary: Consolidated key product insights.

### 4. **Customer Insights Page**
   - **KPIs:**
     - New Customers.
     - Revenue Per Customer.
   - **Visuals:**
     - Donut Charts: Orders by income level and occupation.
     - Line Chart: Trends in total customers and revenue per customer.
     - Table: Top 100 customers by revenue and orders.
   - **Filters:** Customer name, revenue, and order details.

### 5. **Advanced Analysis Pages**
   - **Decomposition Tree:** Analyzed total orders by category, subcategory, and product.
   - **Q&A Section:** Allowed users to ask business questions and get dynamic, visualized answers via a matrix.

---

## Measures and DAX Calculations

The project involved creating several calculated measures and columns using DAX, including:

- **Total Revenue**: Sum of revenue generated.
- **Total Profit**: Revenue minus costs.
- **Return Rate**: Percentage of returned orders.
- **Rolling Calendar Metrics**: Rolling totals for trends.
- **Target Metrics**: Monthly revenue, orders, and profit vs. targets.

---

## Key Learnings

- Mastered data cleaning and transformation in Power Query.
- Improved data modeling skills by implementing a star schema.
- Gained hands-on experience with DAX for creating advanced calculations.
- Enhanced my ability to design interactive dashboards that tell a clear business story.

## Conclusion

This project provided valuable insights into Adventure Works’ data while honing my skills in Power BI. It demonstrates my ability to analyze data, extract actionable insights, and present them through a compelling dashboard.
