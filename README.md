📊 Chocolate Shipments Analysis – Power BI Project
📌 Project Overview
This project analyzes chocolate shipments data to uncover trends, top-performing suppliers, products, and regions, as well as order fulfillment performance.
Using Power BI, I transformed raw shipment records into actionable business insights that could help a chocolate distribution company optimize operations and boost profitability.

📂 Dataset Information
The dataset consists of three main tables:

Shipments – Transaction-level shipment data (Shipment ID, Supplier, Product, Region, Ship Date, Revenue, Boxes Shipped, Order Status)

Dimension Data – Reference tables for suppliers, products, and geographies

Calendar – Date dimension table for time-based analysis

🔍 Data Preparation & Transformations
Performed in Power Query (M):

Removed null/duplicate records

Standardized date formats and extracted Year, Month, Quarter

Merged Dimension Data to replace IDs with descriptive names

Created calculated columns:

Revenue per Box

Shipment Month-Year

Delivery Status Flag (Delivered / Cancelled)

Added a Calendar table for accurate time intelligence calculations

📈 Key Business Questions Addressed
What is the overall shipment performance?

Who are the top suppliers, products, and regions by revenue?

How do monthly shipment volumes and revenue trend over time?

What is the delivery success rate vs. cancellations?

Which months, products, or regions show high cancellations or low revenue efficiency?

📊 Dashboard Features
KPIs:

Total Revenue

Total Boxes Shipped

Delivery Success Rate

Cancellation Rate

Trend Analysis:

Monthly Revenue & Volume chart

Seasonal peaks & dips

Top Performers:

Top 5 Suppliers by Revenue

Top 5 Products by Revenue

Top 5 Regions by Revenue

Order Status Breakdown:

Delivered vs Cancelled shipments

Interactive Filters:

Year, Supplier, Product, Region

💡 Business Insights
Steady revenue growth in peak seasons, with noticeable dips in off-seasons.

Supplier SP01 consistently leads in revenue contribution.

Product P14 is the top-selling SKU across multiple regions.

Region G2 generates the highest revenue, followed by G4 and G6.

Cancellation rate is higher in certain regions, indicating potential logistics or demand issues.

🚀 Potential Business Actions
Strengthen supplier relationships with high-revenue suppliers.

Focus marketing efforts on top-selling products in low-performing regions.

Investigate and resolve high cancellation causes in specific geographies.

Use seasonality trends for inventory and staffing optimization.

📂 Project Files in this Repository
Power BI-D1.pbix → Power BI Dashboard file

sample-chocolate-shipments-data-all-Apr-2025.xlsx → Raw dataset

README.md → Project documentation (this file)

📸 Dashboard Preview
(Add screenshots here from Power BI dashboard)

🛠 Tools & Technologies Used
Power BI – Data modeling, DAX calculations, interactive dashboard design

Power Query – Data cleaning & transformation

Excel – Raw data storage

DAX – Measures and calculated columns

📢 How to View
Download the .pbix file from this repo.

Open it in Power BI Desktop.

Explore the report using the slicers and filters.

If you like this project, ⭐ star the repo and connect with me on LinkedIn!

