# 🏪 Superstore Data Warehouse

## 🔹 Introduction
Superstore Data Warehouse transforms raw sales data into a **normalized PostgreSQL database**.  
It provides a **scalable, reliable backend** for analytics, reporting, and business intelligence dashboards.

This project implements a **full ETL pipeline** to clean, structure, load, and analyze the data efficiently.

---

## ✨ Features
- ✅ **Normalized relational schema**: Customers, Products, Orders, Order Details, Regions  
- ✅ **ETL pipeline** using Python + SQLAlchemy  
- ✅ **Predefined SQL views** for fast analytics  
- ✅ **Key business metrics** like total sales, profit, and top customers  
- ✅ **Dashboard-ready database**  

---

## 🛠 Technology Stack
| Category | Tool / Library |
|----------|----------------|
| Language | Python 3.x |
| Data Processing | Pandas |
| Database | PostgreSQL |
| ORM/ETL | SQLAlchemy |
| Queries | SQL |
| IDE | Jupyter Notebook / VS Code |

---

## 🔄 Project Workflow
1. **Database Creation** – PostgreSQL database `superstore_db`  
2. **Data Modeling & Normalization** – Design tables & relationships  
3. **Data Cleaning** – Remove duplicates, fix missing or inconsistent values  
4. **ETL Data Loading** – Import CSV into PostgreSQL using SQLAlchemy  
5. **SQL Transformations** – Compute metrics such as total sales and average profit  
6. **Analytical Views Creation** – Prepare reusable views for dashboards  

---

## ⚙ Installation
1. Install Python 3.x and PostgreSQL  
2. Install required libraries:  
```bash
pip install pandas sqlalchemy psycopg2
