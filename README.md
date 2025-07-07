# 📊 Power BI Sales Dashboard- RED ECOMMERCE SALES DASHBOARD


This project features an interactive Power BI dashboard built to analyze general sales data across categories, regions, and payment modes. It enables business users to gain insights into revenue, profit trends, and customer purchasing behavior through dynamic visuals and filters.

---

## 🔍 Project Overview

- Built to explore overall sales performance from raw transactional and customer data.
- Offers detailed breakdowns by category, sub-category, state, city, and payment method.
- Allows users to interactively filter, drill down, and slice data for custom analysis.

---

## 📁 Dataset Description

### 1. `Details.csv`
Contains sales transaction-level data:
- `Order ID` – Unique ID for each order  
- `Amount` – Total amount spent in the transaction  
- `Profit` – Profit earned from the sale  
- `Quantity` – Number of units purchased  
- `Category` & `Sub-Category` – Product classification  
- `PaymentMode` – Mode of payment (COD, EMI, Credit Card, etc.)

### 2. `Orders.csv`
Provides customer and order metadata:
- `Order ID` – Used as a primary key to join with transaction data  
- `Order Date` – Date the order was placed  
- `CustomerName` – Name of the customer  
- `State` & `City` – Geographic location of the order

---

## 🧠 Key Features

- 🔗 **Data Modeling**: Joined `Orders.csv` and `Details.csv` using `Order ID` to build a relational data model.
- 📊 **Visualizations**: Includes bar charts, pie charts, donut charts, line and area graphs, maps, and scatter plots.
- 📌 **DAX Measures**: Created calculated metrics like Total Sales, Total Profit, Quantity Sold, and Average Order Value (AOV).
- 🧹 **Power Query**: Cleaned and transformed data (e.g., type conversion, null handling, formatting).
- 🗂 **Dynamic Filtering**: Users can filter by category, sub-category, state, city, date, and payment method.

---

## 💻 Tools & Technologies

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query  
- CSV files

---
