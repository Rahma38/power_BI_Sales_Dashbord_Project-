# 🟣 Power BI Sales Dashboard Project

## 📘 Project Overview
This project focuses on building an interactive Sales Dashboard using Power BI, based on a cleaned and prepared sales dataset. The main goal is to visualize key sales insights, customer trends, and delivery performance through clear, data-driven charts. The dashboard emphasizes data storytelling, clean visual design, and meaningful business insights.

---

## 🏠 Home Page
The Home Page serves as the entry point to the dashboard and provides:  
- Dashboard Title: *Sales Dashboard*  
- Icon Menu with navigation buttons to:  
  - Sales Overview Page  
  - Operations & Delivery Performance Page  
  - Customer Analysis Page  
- Bookmarks were implemented to capture specific page views and states for smooth navigation.  
- Added image and dashboard description explaining what the dashboard does, making it more professional and user-friendly.

---

## 🧹 Data Preparation
Before visualization, the dataset was cleaned and transformed using Excel and Power Query:  
- Removed duplicate records  
- Handled missing values in Ship Date and Order Date  
- Standardized country names using a reference column (*Country_Standardized*)  
- Ensured all date columns use the same format (DD/MM/YYYY)  
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
- KPI Cards:  
  - Total Sales  
  - Total Quantity  
  - Number of Orders  
  - Number of Customers  
  - Average Shipping Days  
- Charts:  
  - Column Chart → Total Sales by Country  
    - Interactivity: Drill Down hierarchy implemented for dynamic analysis: click on a country → Product Categories → Individual Products.  
      Helps uncover which products drive highest sales or have longest shipping times.  
  - Column Chart → Sales by Product Category  
  - Pie Chart → Sales by Ship Mode  
  - Line Chart → Sales Trend over Time  
- Filters (Slicers):  
  - Country  
  - Product Category  
  - Year  

This page gives a high-level view of sales distribution and performance.

---

### 🔹 Page 2: Operations & Delivery Performance
Objective: Analyze shipping efficiency and order patterns.  
Visuals included:  
- Bar Chart → Average Shipping Days by Country  
- Column Chart → Number of Orders per Product Category  
- Line Chart → Shipping Trend Over Time  
- KPIs:  
  - Average Shipping Days  
  - Total Orders  
  - Shipping Performance by Country  

Interactivity:  
- Users can click on country bars in relevant charts to explore deeper insights about shipping performance by products or categories.

---

### 🔹 Page 3: Customer Analysis
Objective: Examine customer distribution, top performers, and purchase behavior.  
Visuals included:  
- Map → Number of Customers by Country  
- Column Chart → Top 10 Customers by Total Sales  
- Matrix → Country, Number of Customers, Top 5 Customers by Number of Orders  
- Bar Chart → Top 5 Customers by Number of Orders  

This page provides insights into customer segmentation and behavior, helping identify key clients and markets.

---

## 🔖 Bookmarks & Navigation
- Bookmarks were added for Home Page and other dashboard pages to enhance user experience.  
- Navigation buttons allow users to move seamlessly between:  
  - Home Page  
  - Sales Overview  
  - Operations & Delivery Performance  
  - Customer Analysis
  -  Each bookmark captures a specific view or page state, making the dashboard interactive like a professional business report.

---
## 🧭 Design and Storytelling
- Consistent color theme across all visuals  
- Titles, page headers, and slicers added for clarity  
- Icons added next to KPIs for better visual communication  
- Transparent background with matching theme colors  
- Clean, focused charts for actionable business insights

---

## 🧠 Insights & Key Findings
- Certain countries and product categories generate the highest sales.  
- Some products have higher sales quantities but lower revenue, indicating pricing differences.  
- Average shipping time remains around 3 days, reflecting efficient delivery.  
- Customer analysis shows key clients and distribution patterns.  
- Sales trends reveal monthly and seasonal fluctuations, supporting better forecasting.

---

## 🛠️ Tools Used
- Excel for initial data cleaning  
- Power Query in Power BI for data transformation  
- Power BI Desktop for visualization and dashboard creation

---

## 💼 Outcome
This project demonstrates the complete process of:  
1. Data Cleaning & Preparation  
2. Data Visualization  
3. Interactive Storytelling through Drill Down, Bookmarks, and Home Navigation  

It highlights how a well-structured Power BI dashboard can transform raw sales and customer data into actionable business insights.

---

## 👩‍💻 Author
Rahma Abdelrazek  
*Data Analyst | Power BI Developer | Excel & Data Visualization Enthusiast*
- Each bookmark captures a specific view or page state, making the dashboard interactive like a professional business report.

---
