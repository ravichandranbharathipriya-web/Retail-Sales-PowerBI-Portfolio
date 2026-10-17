# 📊 Retail Sales Analytics Dashboard

An interactive Power BI project designed to analyze retail sales performance, customer purchasing behaviour, product performance, sales channels, discounts, and promotional activities using synthetic retail transaction data.

## 🎯 Project Objectives

- Analyze retail sales and revenue performance.
- Track daily, monthly, and seasonal sales trends.
- Identify top-performing products and SKUs.
- Understand customer purchasing behaviour.
- Compare sales across stores and sales channels.
- Analyze discount and promotional campaign performance.
- Investigate potential data quality issues.
- Develop interactive dashboards to support data-driven decisions.

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — KPI calculations and analytical measures
- **Microsoft Excel** — Dataset preparation and validation
- **GitHub** — Project documentation and version management

## 📂 Dataset Overview

This project uses synthetic retail sales transaction data and supporting datasets for retail business analysis.

The datasets are uploaded as ZIP archives to simplify the storage and management of large files.

### Dataset Information

The project includes datasets relating to:

- Retail sales transactions
- Customer master data
- Product and SKU information
- Store information
- Inventory snapshots
- Promotional campaigns

The exact files available depend on the contents of the uploaded ZIP archives.

### Sales Transaction Columns

The retail sales transaction dataset includes the following fields:

| Column | Description |
|---|---|
| `date` | Transaction date |
| `receipt_id` | Receipt or transaction identifier |
| `store_id` | Store identifier |
| `sku_id` | Product identifier |
| `customer_id` | Customer identifier |
| `quantity` | Quantity purchased |
| `unit_price` | Unit selling price |
| `total_value` | Recorded transaction-line value |
| `channel` | Sales channel |
| `discount_pct` | Discount percentage |
| `promo_id` | Promotional campaign identifier |

The transaction data covers dates spanning 2022–2025.

## 📈 Key Performance Indicators

Depending on the measures implemented in the Power BI report, the dashboard can include:

- Total Sales and Revenue
- Total Quantity Sold
- Transaction and Receipt Count
- Unique Customers
- Average Order Value
- Monthly Sales Trends
- Sales by Product and Store
- Sales Channel Performance
- Discount and Promotion Analysis
- Inventory Risk Indicators, where supporting data is available
- Advanced Sales Analytics

## 📊 Dashboard Modules

The project covers retail analytics through dashboard pages such as:

1. Executive Overview
2. Sales Trend Analysis
3. Monthly and Seasonal Sales
4. Product Performance
5. Customer Insights
6. Customer Behaviour Analytics
7. Business Insights
8. Regional and Store Sales
9. Revenue Analysis
10. Order and Transaction Analysis
11. Inventory Risk Analytics
12. Advanced Analytics

The final modules depend on the visuals and measures implemented in the Power BI report.

## 🧹 Data Preparation

Data preparation and transformation are performed using Power Query and other applicable data preparation techniques.

Activities include:

- Checking data types and column formats
- Formatting transaction dates
- Validating numeric fields
- Reviewing missing values
- Examining transaction identifiers
- Preparing datasets for Power BI analysis
- Creating DAX measures for analytical reporting

## 📷 Dashboard Screenshots

Dashboard screenshots are available in the `dashboard-screenshots/` folder.

These screenshots showcase the report pages, KPIs, and interactive visualizations.

## 💡 Business Value

This project demonstrates how retail transaction data can help businesses:

- Monitor sales performance over time
- Identify high-performing products and stores
- Understand customer purchasing patterns
- Compare In-Store, Online, and Mobile App sales
- Evaluate discount and promotional activities
- Investigate potential data quality issues
- Make data-driven business decisions

## 📁 Project Structure

- `contaminated_data/` — Dataset files and related data resources
- `dashboard-screenshots/` — Power BI dashboard screenshots
- `RetailSales-PowerBI.pbix` — Power BI report file
- `RetailPulseReport.pdf` — Project report
- `README.md` — Project documentation

Dataset ZIP archives should be extracted before using their contents in Power BI, where required.

## 🚀 How to Use

1. Clone or download this GitHub repository.
2. Open the `contaminated_data/` folder.
3. Download the required dataset ZIP archive or archives.
4. Extract the ZIP files to a local folder.
5. Open `RetailSales-PowerBI.pbix` using Microsoft Power BI Desktop.
6. Update the data source paths if prompted.
7. Confirm that the date, numeric, and identifier columns have the correct data types.
8. Refresh the data if required.
9. Explore the dashboard pages, filters, KPIs, and visualizations.

## 📝 Conclusion

The Retail Sales Analytics Dashboard demonstrates practical skills in data preparation, Power Query, DAX, data analysis, and interactive Power BI reporting. It showcases how retail transaction data can be transformed into useful business insights.

## 👩‍💻 Author

**Bharathi Priya R**

Data Analytics | Power BI | SQL | Excel | DAX
