# Blinkit-Grocery-Sales-Analysis-Dashboard
![Blinkit-Grocery-Sales-Analysis-Dashboard](https://github.com/hussain-data/Blinkit-Grocery-Sales-Analysis-Dashboard/blob/b401c3ebb8512363b3de2bc39da97a398066f35b/blinkit.png)

---

## 📊 Project Overview
This project provides a comprehensive analysis of Blinkit grocery sales data. The primary objective is to uncover sales patterns, identify top-performing product categories and outlets, and understand the key factors driving sales performance. The analysis is performed using SQL for data querying, Python for exploratory data analysis (EDA), and Power BI for creating a dynamic and interactive dashboard.
This project is an end-to-end demonstration of a data analysis workflow, from data cleaning and transformation to insightful visualization.


## 🛠️ Tools Used
* SQL: Used for data extraction, aggregation, and initial transformation. The queries calculate key performance indicators (KPIs) and structure the data for analysis.
* Python: Employed for in-depth exploratory data analysis (EDA) and data cleaning.
* Libraries: Pandas for data manipulation, Matplotlib and Seaborn for creating static visualizations.
* Power BI: The final tool used to build an interactive and visually appealing dashboard that consolidates all insights and allows for dynamic filtering.


## ⚙️ Project Workflow
### 1. Data Sourcing:
The analysis is based on the BlinkIT Grocery Data.csv dataset, which contains detailed information about item sales, outlet characteristics, and customer ratings.
### 2. Data Cleaning & Transformation:
* In the Jupyter Notebook (BlinkitAnalysisPy.ipynb), the Item Fat Content column was standardized by replacing inconsistent values like 'low fat', 'LF', and 'reg' with 'Low Fat' and 'Regular' respectively.
* In the SQL script (SQLQuery.sql), data types were converted using CAST for accurate calculations and clean formatting. The PIVOT function was used to transform data for analyzing fat content sales across different outlet location types.
### 3. Exploratory Data Analysis (EDA):
* Key Performance Indicators (KPIs) such as Total Sales, Average Sales, and Average Ratings were calculated using both SQL and Python to get an initial understanding of the data.
* Visualizations were created in the Jupyter Notebook to explore relationships, such as the distribution of sales by fat content and item type.
### 4. Dashboard Creation:
* An interactive dashboard was developed in Power BI (blinkit.pbix) to present the findings.
* The dashboard includes KPI cards, slicers for filtering by Outlet Location, Size, and Item Type, and various charts (Donut, Bar, Line, and Stacked Bar) to visualize the insights dynamically.
 

## 📈 Key Performance Indicators (KPIs)
* Total Sales: $1.20M
* Average Sales per Item: $141
* Total Number of Items Sold: 8,523
* Average Item Rating: 3.9


## 💡 Key Insights & Findings
* Sales by Fat Content: Low Fat items account for the majority of sales (64.9%) compared to Regular items (35.1%).
* Top Product Categories: Fruits & Vegetables and Snack Foods are the highest revenue-generating categories, indicating high customer demand.
* Outlet Performance:
 * Supermarket Type1 outlets are the top performers, contributing the most to total sales by a significant margin.
 * Medium-sized outlets generate the highest sales revenue.
 * Outlets located in Tier 3 cities show the highest sales figures, followed by Tier 2 and Tier 1.
* Sales Trend by Establishment Year: There was a significant peak in total sales from outlets established in 2018.
 

## 📁 Repository Structure
* BlinkitAnalysisPy.ipynb: Contains the Python code for data cleaning and exploratory data analysis.
* SQLQuery.sql: Includes all the SQL queries used for data extraction and KPI calculation.
* blinkit.pbix: The main Power BI file for the interactive dashboard.
---





