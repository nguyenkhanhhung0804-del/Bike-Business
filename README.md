# 🚲 Bike-Share Revenue & Rider Analysis

An end-to-end data analytics project analyzing bike-sharing **revenue, profitability, rider trends, seasonality, and rider demographics** across 2021–2022 using SQL and Power BI.

## 📊 Project Overview

The objective of this project is to analyze bike-sharing operations and identify key business insights related to revenue, profit, rider activity, and customer behavior.

### Key Metrics

- **3M+** total riders
- **$15M+** total revenue
- **$10.45M+** total profit
- **45%** profit margin

## 🛠️ Tools & Technologies

- **SQL** – Data cleaning, transformation, joins, and calculations
- **Power BI** – Interactive dashboard and data visualization
- **DAX** – KPI and business metric calculations
- **CSV** – Raw datasets

## 🔄 Data Preparation

The project uses separate bike-sharing datasets for 2021 and 2022 along with a cost table.

SQL was used to:

1. Combine the 2021 and 2022 datasets
2. Join the bike-sharing data with the cost table
3. Calculate revenue and profit
4. Prepare the final dataset for Power BI analysis

## 📈 Dashboard

The Power BI dashboard provides an interactive view of bike-sharing business performance.

### Dashboard Features

- **KPI Cards**
  - Total Riders
  - Total Revenue
  - Total Profit
  - Profit Margin

- **KPI Over Time**
  - Monthly rider trends
  - Average revenue
  - Average profit
  - Year-over-year comparison

- **Revenue by Season**
  - Seasonal revenue comparison
  - Identification of the highest-performing season

- **Rider Demographics**
  - Registered vs. casual riders
  - Customer composition analysis

## 💡 Key Insights

- The business generated approximately **$15M in revenue** and **$10.45M in profit**.
- Rider activity and revenue increased significantly during 2022.
- **Season 3** generated the highest revenue at approximately **$4.9M**.
- **Registered riders accounted for approximately 81%** of total rides, while casual riders accounted for approximately 19%.
- Revenue and rider activity show clear **seasonal patterns**, with stronger performance during warmer months.

## 📁 Project Structure

```text
Bike-Share-Analysis/
│
├── bike_share_yr_0.csv
├── bike_share_yr_1.csv
├── cost_table.csv
├── bike_data.sql
├── Bike_Project.pbix
├── Dashboard.png
└── README.md

---

## 👤 Author

**Hung Khanh Nguyen**
