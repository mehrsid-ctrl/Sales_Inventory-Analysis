🛍️ Retail, Sales & Inventory Analytics Project
📄 Description

This project provides a complete Retail Sales and Inventory Analytics workflow — from raw data cleaning in Excel to relational database modeling in MySQL, and finally interactive visual dashboards in Power BI.

It analyzes sales trends, product performance, store operations, and customer insights using a structured, data-driven approach.

The goal is to build a single source of truth for decision-making across retail operations.

🧩 Project Workflow

Phase 1 – Data Cleaning (Excel):

Standardized headers and removed duplicates

Formatted dates (yyyy-mm-dd)

Created helper columns (shipped_flag, has_phone)

Trimmed text and normalized brand/category names

Phase 2 – SQL Database (MySQL):

Created schema: retail_sales

Imported 9 cleaned tables (customers, orders, order_items, etc.)

Established foreign key relationships

Built analytical SQL queries and views (e.g. v_order_revenue, v_order_item_revenue)

Phase 3 – Power BI Dashboard:

Connected directly to MySQL database

Created KPIs: Total Sales, Orders, Avg Order Value

Visualized sales by store, brand, and category

Identified low stock alerts and sales seasonality

📊 Key Insights

Total revenue: $21.3M across 1,614 orders

Store 3 (Central Branch) contributed ~40% of total sales

Electronics and Accessories were top-selling categories

Peak sales during Q4 2022, confirming strong seasonality

Identified low stock for fast-moving products

🛠️ Tools Used

Excel – Data cleaning and preparation

MySQL Workbench – Database schema and SQL analysis

Power BI – Dashboard visualization and insights

(Optional) Python – Additional data exploration and segmentation

📁 Repository Contents
📦 Retail-Sales-Analytics/
├── 📊 data_clean/              # Cleaned Excel/CSV files
├── 🧮 sql_scripts/             # MySQL schema & analysis queries
├── 📈 PowerBI_Dashboard.pbix   # Interactive Power BI dashboard
├── 📄 Final_Report_MehrPathan.docx
└── README.md                   # Project overview and instructions

📌 Author

Mehr Pathan
Data Analytics Project | 2025
