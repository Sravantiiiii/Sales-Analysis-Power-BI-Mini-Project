# Sales Analysis Using Power BI – Mini Project

## 📌 Project Overview
This project analyzes retail sales data using Microsoft Power BI to understand sales performance across regions, products, customers, and salespersons. It includes data cleaning, data modeling, DAX calculations, and interactive report development.

## 🎯 Objectives
- Analyze total revenue, orders, and quantity sold.
- Identify top-performing regions, products, and categories.
- Evaluate salesperson and customer performance.
- Explore monthly sales trends.
- Build an interactive dashboard for business decision-making.

## 🛠️ Tools & Technologies
- Microsoft Power BI
- Power Query
- DAX
- PostgreSQL
- Microsoft Excel

## 📂 Datasets
The project uses five datasets:
- Customers
- Employees
- Products
- Orders
- Order Items

Data preparation included checking duplicates, correcting formatting and date issues, and reviewing missing values and inconsistent records.

## 🔗 Data Modeling
The tables were connected through relationships between customers, employees, products, orders, order items, and a Calendar table. The Calendar table supports date-based analysis.

<img width="467" height="355" alt="data_model" src="https://github.com/user-attachments/assets/b58ad963-69b6-4a75-b6a0-25a89a77a268" />


## 📊 Dashboard Pages

### 1. Executive Overview
- KPI cards for total revenue, order count, total quantity, and revenue per order.
- Monthly revenue trend.
- Revenue by region.
- Region and month slicers.

<img width="710" height="398" alt="executive-overview" src="https://github.com/user-attachments/assets/0a9bdd2a-fcc5-4eda-a6cd-fac7883ad34b" />


### 2. Sales Analysis
- Revenue by salesperson and region.
- Monthly sales trend.
- Filters for month, region, and salesperson.
- Bookmarks for saved report views.

<img width="707" height="395" alt="sales_analysis" src="https://github.com/user-attachments/assets/f259be97-4c09-4c7b-b97a-3052a80eafd0" />


### 3. Product Analysis
- Revenue by product.
- Revenue by product category.
- Interactive product and category analysis.

<img width="711" height="392" alt="product_analysis" src="https://github.com/user-attachments/assets/87f2d1da-9915-4daa-bfe8-8908dbb251bf" />


### 4. Customer Details
- Customer-level revenue, order count, and quantity.
- Revenue by customer.
- Revenue distribution by region.
- Drill-through to detailed customer information.

<img width="707" height="398" alt="customer_details" src="https://github.com/user-attachments/assets/9c7925e8-a9a5-42e1-b5b6-d270c43a86c3" />


## ⚙️ Interactive Features
- Slicers and filters.
- Drill-down and drill-up.
- Customer drill-through.
- Bookmarks for saved report views.
- Navigation buttons between report pages.
- Reset Filters button.
- Row-Level Security (RLS), tested using a North Manager role.

## 📈 Key Findings
- Total revenue: approximately 3.96 million.
- Total orders: 399.
- Total units sold: 2,058.
- The South region generated the highest revenue.
- Electronics was the best-performing category.
- Air Purifier Mini was the top revenue-generating product.

## 💡 Business Recommendations
- Focus on high-performing products and categories.
- Maintain stock of products with strong sales.
- Investigate lower-performing regions.
- Monitor monthly sales trends to support planning.

## 📦 Project Deliverables
- Power BI report (.pbix)
- Excel worksheet (.xlsx)
- Project presentation (.pptx)
- Project documentation (.pdf and .docx)

## ⚠️ Limitations
Year-over-year comparisons require previous-year data for meaningful results. Publishing and sharing through Power BI Service were not completed as part of this project.

## ✅ Conclusion
This project provided hands-on experience in data cleaning, data modeling, DAX, interactive visualizations, and retail sales analysis using Power BI.
