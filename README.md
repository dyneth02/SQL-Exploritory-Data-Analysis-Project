# 📊 SQL Data Analytics Project – Retail Data Warehouse EDA

This project showcases **SQL-based Exploratory Data Analysis (EDA)** on a structured retail data warehouse.  
It includes scripts for database creation, metadata exploration, dimensional profiling, date analysis, metric computation, magnitude breakdowns, and ranking using advanced SQL functions.

---

## 📁 Project Structure

### **00_init_database.sql**
Creates the `DataWarehouseAnalytics` database, defines the `gold` schema, and loads dimension & fact tables via BULK INSERT.  
Tables:  
- `gold.dim_customers`  
- `gold.dim_products`  
- `gold.fact_sales`  
:contentReference[oaicite:0]{index=0}

---

### **01_database_exploration.sql**
Explores metadata using `INFORMATION_SCHEMA`.  
- Lists all tables  
- Inspects columns and data types  
Useful for schema validation before EDA.  
:contentReference[oaicite:1]{index=1}

---

### **02_dimensions_exploration.sql**
Profiles dimension tables (`dim_customers`, `dim_products`).  
Uses `DISTINCT` + `ORDER BY` to understand:  
- Countries  
- Categories & subcategories  
- Product diversity  
:contentReference[oaicite:2]{index=2}

---

### **03_date_range_exploration.sql**
Analyzes temporal boundaries using `MIN()`, `MAX()`, `DATEDIFF()`.  
Includes:  
- First/last order date  
- Youngest/oldest customers  
:contentReference[oaicite:3]{index=3}

---

### **04_measures_exploration.sql**
Computes key business metrics:  
- Total sales, quantity, orders  
- Average price  
- Distinct customers  
- Combined metric report via `UNION ALL`  
:contentReference[oaicite:4]{index=4}

---

### **05_magnitude_analysis.sql**
Breakdown of data magnitude using `GROUP BY`:  
- Customers by country/gender  
- Products by category  
- Average cost per category  
- Revenue by category & customer  
- Item distribution across regions  
:contentReference[oaicite:5]{index=5}

---

### **06_ranking_analysis.sql**
Ranks products and customers using:  
- `TOP`  
- `RANK()`  
- `ROW_NUMBER()`  
Includes:  
- Top & bottom performing products  
- Top revenue-generating customers  
- Customers with fewest orders  
:contentReference[oaicite:6]{index=6}

---

## 🎯 Project Highlights

- Fully SQL-based, no external tools required  
- Clear logical progression from **schema → dimensions → dates → metrics → magnitude → ranking**  
- Uses advanced SQL: window functions, grouping, distinct profiling, metadata queries  
- Excellent template for analytics portfolios and data engineering foundations  

---

## 🚀 How to Use

1. Run `00_init_database.sql` to create and populate the warehouse.  
2. Execute each exploration script in order:  
3. Use any SQL client supporting T-SQL (Azure Data Studio, SSMS).

---

## 🧠 Skills Demonstrated

- Data warehousing fundamentals  
- SQL EDA methodology  
- Window functions (RANK, ROW_NUMBER)  
- Aggregations & grouping  
- Dimensional modeling analysis  
- Schema introspection  
- Retail analytics logic

---

## 🏫 Academic Context
- Built as a personal analytics project inspired by coursework and real-world data warehouse approaches.  
- Suitable for demonstrating SQL proficiency in analytics, BI, and data engineering.

---

## 👨‍💻 Author
D.G.A. DINETH HIRUSHA

