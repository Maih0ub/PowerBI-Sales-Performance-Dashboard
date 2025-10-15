# 🧾 Power BI Sales Performance Dashboard

### 📊 Project Overview
This project presents a comprehensive **Sales Performance Dashboard** built in **Microsoft Power BI**.  
It utilizes a **star schema data model** with multiple dimension tables (Date, Product, Order, Territory, Status) and a central **Fact_Sales** table to deliver powerful business insights.

---

### 🧠 Key Objectives
- Analyze total sales, orders, and average order value across time.
- Track delivery efficiency and identify operational bottlenecks.
- Explore top-performing products and categories.
- Visualize sales distribution by region and order status.

---

### 🧩 Data Model
The data model follows a **dimensional structure**:
- **Fact_Sales:** Sales metrics, quantities, tax, delivery %, and calculated KPIs.
- **Dim_Product:** Product details and hierarchies.
- **Dim_Order:** Order and OrderDetail mapping.
- **Dim_Territory:** Geographical segmentation.
- **Dim_Status:** Order status tracking.
- **Dim_Date:** Central date dimension (Order, Due, and Ship Dates).

---

### 📈 Dashboard Pages
1. **Sales Overview:**  
   KPIs (Total Sales, Total Orders, Growth %, Avg Delivery Days)  
   Line chart (Sales over Time), Map (Sales by Territory), Pie chart (Orders by Status).

2. **Product Analysis:**  
   Top 10 products by sales, product contribution %, and category breakdown.

3. **Operations & Delivery:**  
   Delivery time trends, regional performance, and correlation between delivery % and tax %.

4. **Insights & Recommendations:**  
   Smart narrative summarizing trends, findings, and strategic actions.

---

### ⚙️ Tools & Technologies
- Microsoft Power BI  
- DAX (Data Analysis Expressions)  
- Power Query (ETL)  
- Data Modeling (Star Schema)

---

### 🚀 Key Insights
- Sales increased by **18% YoY**, with strong Q4 growth.  
- Top 10 products generate **62% of total revenue**.  
- Delivery time improved by **1.3 days** on average.  
- Region “North-East” demonstrates the highest delivery efficiency.

---

### 📂 Repository Contents
- `Sales_Dashboard.pbix` → Power BI report file  
- `Sales_Data_Model.xlsx` → Source dataset  
- `README.md` → Documentation  

---

### 👨‍💻 Author
**Mohamed Mayhoub**  
Software & Data Engineer | Power BI Developer  
📧 [momaihoub2692002@gmail.com]  
🌐 [inkedin.com/in/engmomaihoub/]
