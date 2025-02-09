# Sales Data Warehouse and Analytics Project 🚀

Welcome to the **Sales Data Warehouse and Analytics Project** repository!  
This project implements a **Sales Data Warehouse** using the **Star Schema model**, integrating **customer, product, and sales data** to support **business intelligence and analytics**.

---

## 📖 Project Overview  

This project focuses on:  

1. **Data Architecture**: Implementing a modern **Medallion Architecture** with **Bronze, Silver, and Gold** layers.  
2. **ETL Pipelines**: Extracting, transforming, and loading (ETL) data from source systems into a structured warehouse.  
3. **Data Modeling**: Designing a **Star Schema** with **fact and dimension tables** optimized for analytical queries.  
4. **Analytics & Reporting**: Developing SQL-based reports and dashboards for actionable business insights.  

🎯 **Key skills demonstrated in this project:**  
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🚀 Project Requirements  

### **Building the Data Warehouse (Data Engineering)**  

#### **Objective**  
Develop a **modern data warehouse** using **SQL Server** to consolidate sales data, enabling **analytical reporting and informed decision-making**.  

#### **Specifications**  
- **Data Sources**: Import data from **two source systems (ERP and CRM)** provided as CSV files.  
- **Data Quality**: Cleanse and resolve **data quality issues** before analysis.  
- **Integration**: Combine both sources into a **single, user-friendly data model** optimized for analytical queries.  
- **Scope**: Focus on the **latest dataset only** (historical tracking is not required).  
- **Documentation**: Provide **clear documentation** of the data model for business stakeholders and analytics teams.  

---

### **BI: Analytics & Reporting (Data Analysis)**  

#### **Objective**  
Develop **SQL-based analytics** to deliver **detailed insights** into:  
- **Customer Behavior** 📊  
- **Product Performance** 📦  
- **Sales Trends** 💰  

---

## 🏗️ Data Architecture  

This project follows the **Medallion Architecture**, ensuring a structured and scalable data pipeline.  
![Data Architecture](docs/data_architechitecture.png)  

1. **Bronze Layer**: Stores raw data as-is from source systems (ERP, CRM). Data is ingested from CSV files into a **SQL Server Database**.  
2. **Silver Layer**: Processes **data cleansing, standardization, and normalization** to prepare data for analysis.  
3. **Gold Layer**: Houses **business-ready data** modeled into a **Star Schema**, optimized for **reporting and analytics**.  

---

## 📊 Data Model  

The database follows a **Star Schema** design, where **`fact_sales`** serves as the **central fact table**, linked to **`dim_products`** and **`dim_customers`** as dimension tables.  
![Data Model](docs/data_model.png)  

### **Fact Table: `fact_sales`**  
Contains **transactional sales data**, including order details, sales amounts, shipping dates, and product quantities.  

### **Dimension Tables:**  
- **`dim_products`**: Stores product details, categories, costs, and availability.  
- **`dim_customers`**: Contains customer attributes such as demographics and purchase behavior.  

---

## 🛡️ License  

This project is licensed under the **MIT License**.  
You are free to **use, modify, and share** this project with proper attribution.  

📩 **For contributions or inquiries, feel free to open an issue or submit a pull request!** 🚀  
