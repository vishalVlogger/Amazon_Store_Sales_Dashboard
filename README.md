## 📊 Amazon Store Sales Analysis (Power BI Dashboard)
- This project delivers an end-to-end data analysis and visualisation solution for an e-commerce store using Power BI.
- It analyses sales, profit, customer behaviour, returns, and product performance using a modern, multi-page interactive dashboard.

## 🚀 Project Highlights

 - Built a 4-page Power BI dashboard:
    - Executive Summary
    - Sales Insights
    - Customer & Payment Insights
    - Returns & Profitability
 - Designed with a vibrant Theme E UI (bold colours & modern layout).
 - Advanced DAX is used to build KPIs, YoY analysis, and Top-N logic.
 - Cleaned and transformed raw CSV data using Power Query (M).
 - Implemented a fully functional Date Table for time intelligence.

## 🗂️ Dataset

- The dataset includes:
  - Orders, Customers, and Shipping details
  - Sales, Profit, Quantity, Returns
  - Product info (Category, Sub-Category)
  - City, State, Country
  - Dates (Order Date, Ship Date)
- Total rows: 5901
- Total columns: 21

## 🧹 Data Cleaning & Transformation (Power Query)

- Key transformations:
  - Converted date columns using locale-safe parsing (try … otherwise logic)
  - Cleaned numerical fields and standardised types
  - Created new calculated columns:
      - Order Year
      - Order Month
      - Delivery Days
      - Profit Margin
  - Removed duplicates and trimmed all text fields
 
## 🧠 DAX Measures

  - Built more than 25+ measures, including:
    - Total Sales, Total Profit, Total Orders
    - Profit Margin %, Return Rate %
    - Sales YTD, Sales YoY %, Profit YoY %
    - Dynamic Top N Products using parameter table
    - Cumulative and rolling metrics
    - Customer profitability scoring

## 🧩 Dashboard Pages
### 1️⃣ Executive Summary
  - High-level KPIs
  - Sales vs Profit trendline
  - Category-wise sales distribution
  - Interactive slicers (Date, Segment, Payment Mode)

### 2️⃣ Sales Insights
  - State-wise map for Sales & Profit
  - Category/Sub-Category breakdown
  - Top N product analysis
  - Dynamic Top N slicer

### 3️⃣ Customer & Payment Insights
  - Customer segmentation view
  - Payment mode contribution
  - Customer profitability matrix
  - Sales & Orders behaviour trend

### 4️⃣ Returns & Profitability
  - Return rate trend
  - High-return products
  - Profitability heatmap by state
  - Delivery performance analytics

## 🧰 Tools & Technologies
  - Power BI Desktop
  - Power Query (M Language)
  - DAX (Data Analysis Expressions)
  - CSV Dataset
  - Data Modelling

## 📦 Files Included
  - `/Dashboard.pbix` — Power BI project file
  - `/README.md` — Documentation
  - `/Dataset/` — Raw CSV data
  - `/Images/` — Dashboard preview images

## 🏁 How to Use the Dashboard
  - Clone or download this repository
  - Open `Dashboard.pbix` in Power BI Desktop
  - Refresh the dataset or replace the data source
  - Interact with filters, drilldowns & visuals

## 📬 Contact
  - For any queries or collaborations:
    - Vishal — Power BI | Data Analyst | Python Developer
