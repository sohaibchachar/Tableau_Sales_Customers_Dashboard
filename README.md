# Sales & Customer Dashboards - Tableau Project

A comprehensive Tableau dashboard project featuring dynamic Sales and Customer analytics dashboards with support for both EU and Non-EU datasets.

## 📊 Project Overview

This project contains interactive Tableau dashboards designed to analyze sales performance, customer behavior, and business metrics. The dashboards are built with dynamic filtering capabilities and support multiple regional datasets (EU and Non-EU).

## 📁 Project Structure

```
Sales Dashboard Materials/
│
├── Dashboard Icons/                    # Custom icons for dashboard navigation
│   ├── Icon - Customer Dashboard (active).png
│   ├── Icon - Customer Dashboard.png
│   ├── Icon - Filter Hidden.png
│   ├── Icon - Filter Shown.png
│   ├── Icon - Logo.png
│   ├── Icon - Sales Dashboard.png
│   └── Icon - Sales Dashboard(active).png
│
├── EU-Dataset/                        # European dataset (comma-separated decimals)
│   ├── Customers.csv                  # Customer master data
│   ├── Location.csv                   # Geographic location data
│   ├── Orders.csv                     # Order transaction data
│   └── Products.csv                   # Product catalog
│
├── Non-EU Dataset/                     # Non-European dataset (period-separated decimals)
│   ├── Customers.csv                  # Customer master data
│   ├── Location.csv                   # Geographic location data
│   ├── Orders.csv                     # Order transaction data
│   └── Products.csv                   # Product catalog
│
└── Sales & Customer Dashboards (Dynamic).twbx    # Main Tableau workbook
```


## 🎯 Dashboard Features

### Sales Dashboard

**Key Performance Indicators (KPIs):**
1. **Total Sales**: Displays total sales amount with year-over-year percentage change and monthly trend line (showing highest and lowest months)
2. **Total Profit**: Displays total profit with year-over-year percentage change and monthly trend line
3. **Total Quantity**: Displays total quantity sold with year-over-year percentage change and monthly trend line

**Visualizations:**
- **Sales & Profit By Subcategory**: Horizontal bar chart comparing 2023 vs. 2022 sales, with separate profit bars showing 2023 profit by subcategory (includes negative profit indicators)
- **Sales & Profit Trends over Time**: Dual line charts showing:
  - Sales trend with average line indicator
  - Profit trend with average line indicator
  - Color-coded segments (blue for above average, orange for below average)

**Features:**
- Year-over-year comparison (2023 vs. 2022)
- Monthly trend analysis with highest/lowest month indicators
- Interactive tooltips with detailed metrics
- Subcategory-level performance analysis

### Customer Dashboard

**Key Performance Indicators (KPIs):**
1. **Total Customers**: Displays total customer count with year-over-year percentage change and monthly trend line
2. **Total Sales Per Customer**: Displays average sales per customer with year-over-year percentage change and monthly trend line
3. **Total Orders**: Displays total order count with year-over-year percentage change and monthly trend line

**Visualizations:**
- **Customer Distribution by Number of Orders**: Bar chart showing the distribution of customers based on their order frequency (0-8+ orders)
- **Top 10 Customers by Profit**: Detailed table ranking customers by profit, including:
  - Customer name
  - Last order date
  - 2023 profit
  - 2023 sales
  - Number of orders

**Features:**
- Year-over-year comparison (2023 vs. 2022)
- Monthly trend analysis with highest/lowest month indicators
- Customer segmentation by order frequency
- Top customer identification and analysis

### Dynamic Features
- Interactive year selection (2023 focus with 2022 comparison)
- Navigation icons for switching between Sales and Customer dashboards
- Filter controls (funnel icon) for dynamic data filtering
- Responsive design for different screen sizes
- Custom navigation icons for seamless dashboard switching

## 🚀 Getting Started

### Prerequisites
- Tableau Desktop (version 2020.1 or later recommended)
- Access to the `.twbx` workbook file

### Installation

1. **Clone or download** this repository to your local machine

2. **Open Tableau Desktop**

3. **Open the workbook**:
   - Navigate to `File > Open`
   - Select `Sales & Customer Dashboards (Dynamic).twbx`

4. **Connect to data sources** (if needed):
   - The workbook should already have data connections configured
   - If data sources need to be updated, right-click on data sources in the left panel and select "Edit Data Source"
   - Point to the appropriate CSV files in either `EU-Dataset/` or `Non-EU Dataset/` folders


