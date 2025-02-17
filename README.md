# ☕ Coffee Shop Sales

## 📌 Project Overview
The **Coffee Shop Sales** Power BI dashboard provides a **comprehensive analysis of sales performance** across different store locations, time periods, and product categories. This dashboard enables data-driven decision-making by identifying **sales trends, peak selling hours, top-performing products, and location-based performance variations**. 

## 🎯 Objectives
- **Total Sales Analysis:** Track sales figures, month-over-month changes, and revenue trends.
- **Order & Quantity Analysis:** Understand the number of orders and quantity sold over time.
- **Sales Trends:** Identify peak and off-peak sales periods using daily trends, heat maps, and MoM comparisons.
- **Store Location Insights:** Compare store performance across multiple locations.
- **Top Products & Categories:** Identify best-selling product categories and top 10 individual products.
- **Time-Based Performance:** Evaluate weekday vs. weekend sales, and sales across different hours of the day.

## 🛠️ Technologies Used
- **Power BI Desktop** for data visualization and dashboard creation.
- **Excel** as the data source for importing and transforming raw sales data.
- **DAX (Data Analysis Expressions)** for calculated measures and KPIs.
- **Power Query** for data cleaning and transformation.

---

## 🚀 Setup Instructions

### **Step 1: Install Power BI Desktop**
- Download and install **[Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)**.

### **Step 2: Load Data from Excel**
1. Open **Power BI Desktop**.
2. Click **"Home" > "Get Data" > "Excel"**.
3. Browse and select the **Coffee_Shop_Sales.xlsx** file.
4. Click **"Load"** to import the dataset.

### **Step 3: Transform Data using Power Query**
1. Click **"Transform Data"** to open **Power Query Editor**.
2. Apply necessary transformations such as:
   - Removing duplicates.
   - Changing data types (e.g., dates, currency).
   - Creating new calculated columns (if needed).
3. Click **"Close & Apply"** to save changes.
4. Click on 'Model View' and establish a one-to-many relationship between Transactions and Date Table by connecting the 'Date' column from the Date Table to 'transaction_date' in Transactions tables.

---

## 📊 Dashboard Creation & Usage Instructions

### **1️⃣ Total Sales Overview**
- **Visual Type:** KPI Card
- **Purpose:** Displays **total sales, total orders, and total quantity sold**.
- **Interaction:** Monthly comparisons highlight changes vs. the previous month.

### **2️⃣ Calendar Heat Map**
- **Visual Type:** Heatmap
- **Purpose:** Shows **daily sales performance**, with color intensity representing sales volume.
- **Interaction:** Hover over any date to see total sales, orders, and quantity for that day.

### **3️⃣ Sales by Weekday vs. Weekend**
- **Visual Type:** Bar Chart
- **Purpose:** Compares sales performance on weekdays vs. weekends.
- **Insight:** Helps identify peak sales days and whether weekends outperform weekdays.

### **4️⃣ Sales by Store Location**
- **Visual Type:** Bar Chart
- **Purpose:** Displays **sales performance for each store location**.
- **Interaction:** Shows **month-over-month (MoM) sales differences** for trend tracking.

### **5️⃣ Daily Sales Analysis**
- **Visual Type:** Line Chart with Average Line
- **Purpose:** Tracks **daily sales trends within a selected month**.
- **Insight:** Highlights days exceeding or falling below the average daily sales.

### **6️⃣ Sales by Product Category**
- **Visual Type:** Bar Chart
- **Purpose:** Displays sales contribution by different **product categories** (Coffee, Tea, Bakery, etc.).
- **Interaction:** Allows users to analyze which categories generate the highest revenue.

### **7️⃣ Top 10 Products by Sales**
- **Visual Type:** Table
- **Purpose:** Lists the **top-selling products** ranked by revenue.
- **Insight:** Helps businesses focus on high-demand products.

### **8️⃣ Sales by Days & Hours**
- **Visual Type:** Heatmap
- **Purpose:** Visualizes sales distribution **hourly across different days of the week**.
- **Interaction:** Hovering over a cell shows sales, orders, and quantity metrics for a specific hour.

---

## 📌 Additional Features
- **Dynamic Filters & Slicers:** Allows selection of months, locations, and product categories for in-depth analysis.
- **Tooltips & Hover Metrics:** Interactive tooltips provide detailed breakdowns for each visualization.
- **Automated Data Refresh:** Ensures up-to-date insights from the connected dataset.
