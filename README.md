# blinkit-data-analysis-
 Python Project | Data Analysis Python Project | Blinkit Analysis
<img width="753" height="754" alt="image" src="https://github.com/user-attachments/assets/d607fc16-a9d0-4f87-9ac8-31cf942f66fd" />
# 🛒 Blinkit Sales & Inventory Analysis Dashboard

## 📌 Project Overview
This project provides a comprehensive analysis of Blinkit’s sales performance, customer satisfaction, and inventory distribution. By leveraging Power BI, I transformed complex retail data into actionable insights that help stakeholders optimize inventory and improve regional sales strategies.

## 🎯 Business Objectives
* Revenue Growth: Analyze the impact of product attributes (Fat Content, Item Type) on total sales.
* Operational Efficiency:** Evaluate outlet performance based on size, location (Tier 1/2/3), and establishment age.
*Customer Experience:** Monitor average ratings to identify high-performing product categories.

## 📊 Key Performance Indicators (KPIs)
* Total Sales: $1.20M (Overall revenue generated)
* Average Sales: $141 (Revenue per transaction)
* Number of Items: 8,523 (Diversity of product inventory)
* Average Rating: 3.9/5.0 (Customer satisfaction index)

## 🔍 Data Visualizations & Logic
1.  Sales by Fat Content (Donut Chart): Analyzes the revenue split between Low Fat vs. Regular items, cross-referenced with average ratings.
2.  Item Type Performance (Bar Chart): Identifies top-performing categories (Fruits, Snacks, Household) to prioritize stock.
3.  Outlet Establishment Trend (Line Chart): Correlates the age of an outlet with its sales maturity and growth trajectory.
4.  Geographic Distribution (Funnel Map):Visualizes sales across Tier 1, 2, and 3 locations to assist in logistics planning.
5.  Inventory by Size (Pie Chart): Maps sales against Small, Medium, and Large outlet footprints.

## 🛠️ Technical Implementation
* Data Cleaning: Used Power Query for handling missing values and data type normalization.
* DAX Formulas:`Total Sales = SUM(SalesTable[Sales])`
     `Average Rating = AVERAGE(SalesTable[Rating])`
* Data Modeling:Established a Star Schema to optimize filter performance across multiple dimensions (Outlet, Item, Location).

## 💡 Strategic Recommendations
Expansion Strategy: Focus on Tier 3 locations, which show the highest untapped revenue potential.
* Inventory Mix:Increase 'Regular' fat content stock in older supermarkets while testing health-oriented 'Low Fat' bundles in Tier 1 cities.
* Underperformers: Review outlets established post-2018 that show lower-than-average sales despite high item visibility.

<img width="1186" height="677" alt="image" src="https://github.com/user-attachments/assets/ae40ff0d-5be8-46f0-a8b5-a1a67c45def1" />



