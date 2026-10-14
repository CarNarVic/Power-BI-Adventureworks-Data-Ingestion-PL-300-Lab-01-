# Power BI-Adventureworks-Data Ingestion (PL-300 Lab 01)
Data ingestion and environment setup for AdventureWorksDW2020 using SQL Server 2025 and Power BI Desktop (PL-300 Lab 01)

# 📊 AdventureWorks Data Ingestion & Setup (PL-300 Lab 01)

## 📌 Project Overview
This project covers the initial setup and data ingestion phase for the AdventureWorksDW2020 dataset as part of the Microsoft PL-300 (Power BI Data Analyst) certification labs.

The primary goal was to establish a local relational database environment using SQL Server 2025, handle secure authentication, and connect Power BI Desktop to import transactional and dimensional data.

---

## 🛠️ Tech Stack & Tools
- **Power BI Desktop** (Power Query)
- **SQL Server 2025 Developer Edition**
- **SQL Server Management Studio (SSMS)**
- **AdventureWorksDW2020 Database**

---

## 🚀 Key Tasks Completed
1. **Local Server Setup:** Configured a local instance of SQL Server 2025 and SSMS.
2. **Database Restoration:** Restored `AdventureWorksDW2020.bak` onto `localhost`.
3. **Security & Authentication:** Configured Windows Authentication and enabled *Trust Server Certificate* for secure local connectivity.
4. **Data Connection:** Established a connection between Power BI Desktop and SQL Server to import dim/fact tables into Power Query.

---

## 📁 Project Structure
- `AdventureWorksDW2020` database connected via `localhost`.
- Tables loaded for analysis: `DimEmployee`, `DimEmployeeSalesTerritory`, `DimProduct`, `DimReseller`, `DimSalesTerritory`, `FactResellerSales`


---

*Project completed as part of the PL-300 Data Analyst Learning Path.*
