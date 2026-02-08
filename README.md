🛒 E-Commerce Sales Analysis

📁 Project Structure
│
├── 📂 data
│   ├── 📂 raw
│   │   └── 📄 sales_raw.csv
│   │
│   └── 📂 processed
│       └── 📄 sales_cleaned.csv
│
├── 📂 notebooks
│   ├── 📓 01_data_cleaning.ipynb
│   ├── 📓 02_feature_engineering.ipynb
│   ├── 📓 03_eda.ipynb
│   └── 📓 04_analysis.ipynb
│
├── 📂 scripts
│   ├── 🐍 data_cleaning.py
│   └── 🐍 analysis.py
│
├── 📂 powerbi_dashboard
│   └── 📊 ecommerce_sales_dashboard.pbix
│
├── 📂 images
│   └── 🖼 dashboard_preview.png
│
├── 📂 docs
│   └── 📄 project_overview.md
│
├── 📄 README.md
│
├── 📄 requirements.txt
│
└── 📄 .gitignore

##📌 Project Introduction

This project analyzes e-commerce sales data with a focus on the electronics category
and high-value orders. The goal is to track sales, profit, and regional performance
using Excel, Python, and Power BI.

##📂 Raw Data Collection

Raw data was collected in CSV and Excel format.
The dataset contains customer, product, sales, profit, region, and shipping details.
The data required cleaning before analysis.

🔍 Project Overview

The project aims to analyze e-commerce sales to track sales, profit, high-value orders,
and regional performance. Data was cleaned and transformed using Excel and Python,
and then visualized using an interactive Power BI dashboard.

🛠 Tools & Technologies Used

* Excel – Initial data review and formatting
* Python (Pandas, NumPy) – Data cleaning and filtering
* Power BI – Data modeling, DAX, and dashboard creation
  
🧹 Data Cleaning & Preprocessing (NumPy & Pandas)
  
* Removed missing values using imputation
* Removed duplicate records
* Corrected data types for numeric and categorical columns
* Standardized data for accuracy and consistency
  
➕ Create New Columns
  
* Created Total Sales column (Unit Price × Quantity)
* Created Profit column
* Prepared structured data for analysis
  
🔎 Data Filtering
  
* Filtered Electronics category data
* Identified high-value orders
* Performed region-wise and gender-wise analysis
  
📈 Power BI – Data Modeling & DAX
  
* Imported cleaned data into Power BI
* Created DAX measures:
  - Total Sales
  - Total Profit
  - Total Orders
  - Delivery Rate (%)
    
📊 Dashboard

An interactive Power BI dashboard was created to visualize sales, profit,
region-wise performance, product-wise sales, and delivery status.

🔑 Key Insights

* Total profit is around 45K, showing the business is profitable
* Laptops and smartphones are the top-selling products
* Around 77% of orders are successfully delivered
* Electronics category shows strong customer demand
  
💼 Business Impact
  
* Tracks sales and profit performance
* Identifies top-performing regions and products
* Improves focus on high-value orders
* Enables data-driven decision making
  
🚀 Future Improvements
  
* Advanced customer and trend analysis
* Automated real-time dashboard
* Improved delivery and profit tracking
  
✅ Conclusion
  
The project shows that sales targets were achieved and the business is profitable.
Electronics generate the highest sales, and the South region performs best.
