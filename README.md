# ECOMMERCE SALES DASHBOARD 📊  

A fully interactive **Power BI dashboard** to analyze Ecommerce sales performance using order and customer data.  
This project helps understand **revenue trends, customer behavior, and product performance** at a glance.

---

## 🚀 Project Overview  

This dashboard is built to answer key business questions like:

- How are **sales performing over time**?
- Which **states / cities / regions** generate the most revenue?
- Who are the **top customers** and **top-selling products**?
- What is the **best-performing category** or sub-category?
- How do **order status** and **payment methods** affect revenue?

It is a great **portfolio project** to showcase skills in:
- Data cleaning & transformation  
- Data modeling in Power BI  
- Building interactive dashboards for business stakeholders  

---

## 📂 Dataset  

The project uses two main CSV files:

1. **Orders.csv**  
   - Order ID  
   - Order Date  
   - Ship Date  
   - Customer & Region details  
   - Order Status  
   - Payment info (COD/Online etc.)  

2. **Details.csv**  
   - Order ID (for relationship with Orders table)  
   - Product Name / Category / Sub-Category  
   - Quantity  
   - Unit Price  
   - Discount  
   - Total Sales / Profit (if available)  

Both datasets are joined in Power BI using **Order ID** as the key.

---

## 📊 Key Metrics & KPIs  

Some of the important metrics tracked in the dashboard:

- ✅ **Total Sales**
- ✅ **Total Orders**
- ✅ **Total Quantity Sold**
- ✅ **Average Order Value (AOV)**
- ✅ **Sales by Category / Sub-Category**
- ✅ **Top N Products / Customers**
- ✅ **Sales by Region / State / City**
- ✅ **Sales by Payment Mode**
- ✅ **Order Status Breakdown**

---

## 🧩 Dashboard Features  

The dashboard contains multiple visuals, such as:

- **KPI Cards** – high-level view of Total Sales, Orders, AOV, etc.  
- **Line / Area Chart** – sales trend over time (daily/monthly/yearly).  
- **Bar / Column Charts** – sales by category, product, region, and customer.  
- **Donut / Pie Chart** – payment mode split, order status split.  
- **Map (if used)** – geographical sales distribution by state/city.  
- **Interactive Filters (Slicers)** for:
  - Date Range
  - Region / State / City
  - Category / Sub-Category
  - Payment Mode
  - Order Status  

Users can interact with slicers to analyze sales from different angles.

---
![Ecommerce Sales Dashboard](./Screenshot%202025-12-10%20224254.png)
---

## 🛠️ Tech Stack  

- **Power BI Desktop**
- **CSV Files** (`Orders.csv`, `Details.csv`)
- **Data Modeling & DAX** (for calculated columns/measures)
- Basic **data cleaning & transformation** using Power Query

---

## 📥 How to Use This Project  

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/Shashank-Sen/ECOMMERCE_SALES_DASHBOARD.git

