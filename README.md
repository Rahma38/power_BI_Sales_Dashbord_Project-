# 🟣 Power BI Sales Dashboard Project  

## 📘 Project Overview  
This project focuses on building an interactive Sales Dashboard using Power BI, based on a cleaned and prepared sales dataset.  
The main goal is to visualize key sales insights, shipping performance, and customer trends through clear and data-driven charts.  
The project emphasizes data storytelling, clean visual design, and meaningful business insights.

---

## 🧹 Data Preparation  
Before visualization, the dataset was cleaned and transformed in Excel and Power Query to ensure accuracy and consistency:

- Removed duplicate records  
- Handled missing values in Ship Date and Order Date  
- Standardized country names using a reference column (Country_Standardized)  
- Ensured all date columns used the same format (DD/MM/YYYY)  
- Added calculated columns and measures:  
  - Shipping Days = DATEDIFF(Order_Date, Ship_Date, DAY)  
  - Total Sales = Quantity * Unit_Price  
  - Average Shipping Days  
  - Number of Orders  
  - Total Quantity

---

## 📊 Dashboard Pages  

### 🔹 Page 1: Sales Overview  
Objective: Provide a summary of sales performance and customer insights.  

Visuals included:
- KPIs Cards:  
  - Total Sales  
  - Total Quantity  
  - Number of Orders  
  - Number of Customers  
  - Average Shipping Days  

- Charts:  
  - Bar Chart → *Total Sales by Country*  
  - Column Chart → *Sales by Product Category*  
  - Pie Chart → *Sales by Ship Mode*  
  - Line Chart → *Sales Trend over Time*  

- Filters (Slicers):  
  - Country  
  - Product Category  
  - Year  

This page provides a clear high-level view of overall sales distribution and performance.

---

### 🔹 Page 2: Shipping & Performance  
Objective: Analyze shipping efficiency and order patterns.  

Visuals included:
- Bar Chart: *Average Shipping Days by Country*  
- Column Chart: *Number of Orders per Product Category*  
- Line Chart: *Shipping Trend Over Time*  
- KPIs:  
  - Average Shipping Days  
  - Total Orders  
  - Shipping Performance by Country  

Interactivity:  
A Drill Down hierarchy was implemented to make the dashboard more dynamic and insightful.  
Users can click on a country to drill down into Product Categories, and then further into individual Products.  
This interactive analysis helps uncover which products drive the highest sales or have the longest shipping times in each country.

---

## 🔖 Bookmarks & Navigation  
To enhance user experience, Bookmarks were added for smooth navigation between dashboard pages.  
Each bookmark captures a specific view or page state, allowing users to move between:
- Sales Overview  
- Shipping & Performance  

Navigation buttons were placed on the pages, so users can move back and forth seamlessly.  
This feature makes the dashboard behave like an interactive business report rather than static pages.

---

## 🧭 Design and Storytelling  
To make the dashboard more interactive and professional:
- Used a consistent color theme across all visuals  
- Added title section and page header with slicers  
- Used icons next to KPIs for better visual communication  
- Applied a transparent background with matching theme colors  
- Ensured charts are clean and focused on delivering business insights  

---

## 🧠 Insights & Key Findings  
- Certain countries and product categories generated the highest sales.  
- Some products showed higher sales quantities but lower revenue, indicating pricing differences.  
- Average shipping time remained around 3 days, reflecting efficient delivery performance.  
- Sales trends revealed clear monthly and seasonal fluctuations, supporting better forecasting and planning.

---

## 🛠️ Tools Used  
- Excel for initial data cleaning  
- Power Query (in Power BI) for data transformation  
- Power BI Desktop for visualization and dashboard creation  

---
## 💼 Outcome  
This project demonstrates the complete process of:
1. Data Cleaning & Preparation  
2. Data Visualization  
3. Interactive Storytelling through Drill Down and Bookmarks

It highlights how a well-structured Power BI dashboard can transform raw sales data into actionable business insights.

---

## 👩‍💻 Author  
Rahma Abdelrazek  
*Data Analyst | Power BI Developer | Excel & Data Visualization Enthusiast*
