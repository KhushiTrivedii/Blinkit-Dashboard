# Blinkit Grocery Data Analysis Dashboard

An interactive Power BI dashboard designed to analyze Blinkit grocery sales performance across product categories, fat-content segments, outlet locations, outlet sizes, and outlet types. The project transforms raw grocery data into meaningful visual insights to support data-driven understanding of product sales and outlet performance.

## 📌 Project Overview

### Short Description / Purpose

The Blinkit Grocery Data Analysis Dashboard explores sales trends, product category performance, fat-content preferences, outlet characteristics, and customer ratings. Built using Microsoft Power BI, the dashboard combines key performance indicators (KPIs), comparative visualizations, and interactive filters to help users understand sales distribution and identify high-performing product categories and outlet segments.

The project demonstrates practical skills in data cleaning, DAX calculations, data visualization, interactive reporting, and exploratory business analysis.

## 🛠️ Tech Stack

The dashboard was developed using the following tools and technologies:

- 📊 **Power BI Desktop** – Created KPI cards, charts, the outlet performance matrix, slicers, and interactive dashboard elements.
- 🧹 **Power Query** – Cleaned and standardized inconsistent categorical values and inspected data quality.
- 🧮 **DAX (Data Analysis Expressions)** – Created measures for total sales, average sales, item count, and average ratings.
- 📈 **Data Visualization & Reporting** – Presented sales comparisons and outlet performance through interactive visuals.
- 🔄 **Field Parameters** – Enabled users to switch between metrics in selected charts.

## 📂 Data Source

**Source:** Blinkit Grocery Data (Excel dataset used in the tutorial-based project).

The dataset contains approximately 8,523 rows and 12 columns describing grocery products, sales, ratings, and outlet characteristics.

Key fields include:

- **Product Information:** Item Identifier, Item Type, Item Fat Content, and Item Weight.
- **Sales & Customer Metrics:** Sales, Rating, and Item Visibility.
- **Outlet Information:** Outlet Identifier, Outlet Establishment Year, Outlet Location, Outlet Size, and Outlet Type.

The data was imported into Power BI and inspected using Table View and Power Query. Inconsistent fat-content labels were standardized before creating the dashboard visuals.

## 🎯 Features & Highlights

### 1. Business Problem

Grocery retailers need to understand which product categories generate the most sales, how performance varies across outlet locations and sizes, and whether sales patterns differ by product characteristics. Reviewing these factors separately can make it difficult to identify high-performing segments and compare outlet performance consistently.

This dashboard brings these dimensions together in one interactive report, allowing users to explore sales performance across products and outlets and investigate patterns through filters.

### 2. Goal of the Dashboard

The primary objectives of this project are to:

- Monitor overall sales performance through key KPIs.
- Compare sales across item types and fat-content categories.
- Analyze sales by outlet location, size, type, and establishment year.
- Compare average sales, item counts, and average ratings across product categories.
- Enable interactive filtering by outlet location, outlet size, and item type.
- Present business metrics in a clear visual format to support exploratory analysis and decision-making.

### 3. Walkthrough of Key Visuals

#### 📊 KPI Overview

The dashboard begins with four key performance indicators:

- **Total Sales:** Displays the total value recorded in the Sales field.
- **Average Sales:** Shows the average value of the Sales field.
- **Number of Items:** Displays the number of rows in the dataset.
- **Average Rating:** Summarizes the average rating recorded in the dataset.

These KPIs provide a quick overview of the dataset's sales performance and customer ratings.

#### 🥧 Sales by Fat Content

- **Donut Chart:** Compares sales across Low Fat and Regular product categories.
- **Metric Selection:** Allows users to switch between supported metrics, including total sales, average sales, number of items, and average ratings.
- **Purpose:** Helps compare performance across fat-content segments.

#### 📍 Fat Content by Outlet Location

- **Stacked Bar Chart:** Compares fat-content categories across Tier 1, Tier 2, and Tier 3 outlet locations.
- **Metric Selection:** Allows comparisons using different supported measures.
- **Purpose:** Helps explore how product-segment performance varies across outlet tiers.

#### 🛒 Item Type Analysis

- **Bar Chart:** Compares product categories using the selected metric.
- **Category Comparison:** Supports analysis of sales, item counts, and average ratings by item type.
- **Purpose:** Helps identify leading product categories and compare their performance across different measures.

#### 📈 Outlet Establishment Analysis

- **Line Chart:** Displays total sales by outlet establishment year.
- **Trend Analysis:** Helps compare sales associated with outlets established in different years.
- **Purpose:** Provides a historical view of outlet performance and highlights years that may warrant further investigation.

#### 🏬 Sales by Outlet Size

- **Donut Chart:** Compares total sales across Small, Medium, and High outlet-size categories.
- **Purpose:** Helps identify which outlet-size segments contribute the most to total sales.

#### 📍 Sales by Outlet Location

- **Funnel Chart:** Compares total sales across Tier 1, Tier 2, and Tier 3 outlet locations.
- **Purpose:** Highlights differences in sales contribution across outlet tiers.

#### 📋 Outlet Type Performance Matrix

The matrix provides a consolidated comparison of outlet types using the following metrics:

- Total Sales
- Number of Items
- Average Sales
- Average Ratings
- Average Item Visibility

**Purpose:** Enables users to compare outlet types across multiple performance indicators in a single visual.

#### 🎛️ Interactive Filters & Cross-Filtering

The dashboard includes slicers for:

- Outlet Location
- Outlet Size
- Item Type

Users can select a category to filter the dashboard and explore the corresponding results. Chart interactions are configured to filter other visuals where appropriate, making it easier to investigate specific segments.

### 4. Business Impact & Key Insights

Based on the tutorial's interpretation of the dashboard, the following observations can be explored:

- **Overall Performance:** The dashboard reports approximately 1.2 million in total sales, average sales of around 141, 8,523 dataset rows, and an average rating of approximately 3.9.
- **Fat-Content Distribution:** Low Fat products account for approximately 65% and Regular products approximately 35% of the distribution described in the tutorial. The exact measure and percentages should be verified in the report before drawing conclusions.
- **Outlet Location:** Tier 3 outlets contribute the highest sales, followed by Tier 2 and Tier 1 outlets in the tutorial's comparison.
- **Product Category Performance:** Fruits and Vegetables are identified as the leading category by sales, followed by Snack Foods and Household items.
- **Outlet Establishment:** Outlets established in 2018 appear among the stronger performers in the tutorial's chart. This comparison alone does not establish that the outlet's establishment year caused higher sales.
- **Outlet Size:** Medium outlets show the highest sales, followed by Small outlets, while the High-size category records the lowest sales in the tutorial's interpretation.
- **Customer Ratings:** The average rating of approximately 3.9 may warrant further investigation into customer feedback and service quality.

**Potential Business Applications**

- **Sales Performance Monitoring:** Track headline KPIs and compare performance across product and outlet segments.
- **Product Analysis:** Identify categories contributing strongly to sales and examine differences across product characteristics.
- **Outlet Performance Analysis:** Compare sales across locations, outlet sizes, outlet types, and establishment years.
- **Customer Experience Analysis:** Monitor average ratings and identify areas for further investigation.
- **Further Investigation:** Explore low-performing segments and validate possible explanations using inventory, pricing, operational, and customer feedback data.


## 📷 Screenshots / Demo

### 1. Blinkit Dashboard Overview

`Snapshot of Dashboard.png`

## 📁 Repository Contents

- `README.md` – Project overview, tools, methodology, dashboard features, and key insights.
- `Blinkit_Dashboard.pbit` – Power BI report file.
- `Snapshots` – Dashboard screenshots.

## 🚀 Conclusion

This project demonstrates how Power BI can transform raw grocery data into an interactive analytical dashboard. By combining data cleaning, DAX measures, KPI reporting, product comparisons, and outlet-level analysis, the dashboard provides a structured way to explore grocery sales performance.

The project also demonstrates the value of interactive reporting: users can filter the data by product type, outlet size, and location to investigate specific segments rather than relying only on high-level totals.

The dashboard serves as a foundation for further analysis, such as comparing sales with profit margins, inventory availability, discounts, and customer feedback to develop more comprehensive business insights.
