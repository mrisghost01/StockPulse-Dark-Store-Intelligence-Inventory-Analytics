# 📦 StockPulse — Dark Store Intelligence & Inventory Analytics Platform

<div align="center">

### End-to-End Retail Analytics & Business Intelligence Project

StockPulse is a comprehensive Data Analytics project designed to analyze dark store operations, sales performance, inventory movement, and fulfillment efficiency using SQL and Power BI.

It transforms raw operational retail data into actionable business insights through interactive dashboards, KPI monitoring, and inventory intelligence reporting.

---

![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge\&logo=powerbi)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue?style=for-the-badge\&logo=mysql)
![DAX](https://img.shields.io/badge/DAX-Measures-orange?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-green?style=for-the-badge)

</div>

---

# 📖 1. Project Overview

Dark stores operate in highly dynamic environments where inventory availability, order fulfillment, and demand forecasting directly affect customer satisfaction and operational efficiency.

StockPulse was developed to simulate a real-world retail analytics environment where operational data is analyzed to uncover:

* Revenue growth patterns
* Inventory shortages
* Product demand behavior
* Purchase order delays
* Store-level performance
* Fulfillment bottlenecks
* Customer purchasing trends

The project combines data modeling, SQL analytics, DAX calculations, and Power BI storytelling to create a business-focused analytics solution.

---

# 🎯 2. Business Problem Statement

Retail and dark store businesses often struggle with:

* Frequent low-stock situations
* Delayed replenishment cycles
* Poor inventory visibility
* Uneven product demand
* Inefficient purchase order tracking
* Lack of centralized KPI monitoring

Without analytics, businesses face operational inefficiencies and revenue loss.

StockPulse solves this by providing a centralized intelligence dashboard that enables data-driven operational decision-making.

---

# 🛠 3. Technology Stack

| Technology            | Purpose                           |
| --------------------- | --------------------------------- |
| SQL                   | Data querying & schema management |
| Power BI              | Dashboard & visualization         |
| DAX                   | KPI calculations & measures       |
| Excel / CSV           | Dataset storage                   |
| Data Modeling         | Table relationships               |
| Business Intelligence | Decision support analytics        |

---

# 📂 4. Project Structure

```bash
StockPulse/
│
├── datasets/                     # Raw CSV datasets
├── sql/                          # Database schema & SQL scripts
├── notebooks/                    # EDA & validation notebooks
├── dashboard/                    # Power BI files
├── screenshots/                  # Dashboard preview images
├── diagrams/                     # Data model & architecture diagrams
├── README.md
│
└── StockPulse_Dashboard.pbix
```

---

# 🗃 5. Dataset Information

The project includes multiple interconnected datasets representing a dark store ecosystem.

| Table           | Description                     |
| --------------- | ------------------------------- |
| Orders          | Customer order information      |
| Order Items     | Product-level transactions      |
| Inventory       | Daily inventory tracking        |
| Products        | Product catalog                 |
| Categories      | Product classifications         |
| Stores          | Store-level information         |
| Calendar        | Date intelligence               |
| Purchase Orders | Supplier replenishment tracking |

### Dataset Scale

* 42K+ Orders
* 141K+ Order Items
* 780K+ Total All Inventory Records
* Multiple store locations
* Multi-category retail products

---

# 📊 6. Dashboard Modules

## 🔹 Executive Overview Dashboard

Provides a high-level snapshot of business performance.

### KPIs Included

* Total Revenue
* Total Orders
* Average Order Value
* Average Basket Size
* Unique Products
* Store Count

### Business Insights

* Revenue showed stable month-over-month growth
* High-performing stores contributed major revenue share
* FMCG products dominated total sales

---

## 🔹 Sales & Demand Analysis

Focused on customer purchasing behavior and product demand patterns.

### Visuals Included

* Revenue by Zone
* Orders by Time Slot
* Top Performing Stores
* Monthly Order Trends
* Top Selling Products

### Insights Generated

* Evening hours generated maximum order volume
* Fruits & Vegetables category led sales
* Certain regions consistently outperformed others

---

## 🔹 Inventory & Fulfillment Analysis

Tracks inventory health and operational fulfillment efficiency.

### Visuals Included

* Low Stock Alerts
* Purchase Order Status
* Reorder Frequency
* Category-wise Stock Distribution
* Store-wise Inventory Trends

### Insights Generated

* Multiple products repeatedly reached low-stock levels
* Delayed purchase orders affected fulfillment performance
* High-demand products required faster replenishment cycles

---

# 🧠 7. Data Analytics Workflow

```text
Data Collection
      ↓
Data Cleaning & Validation
      ↓
SQL Schema Creation
      ↓
Data Modeling
      ↓
DAX KPI Development
      ↓
Dashboard Design
      ↓
Business Insight Generation
```

---

# 📈 8. Key KPIs & Metrics

The project focuses on operational and business KPIs such as:

| KPI                     | Purpose                      |
| ----------------------- | ---------------------------- |
| Total Revenue           | Overall sales performance    |
| Average Order Value     | Customer spending behavior   |
| Basket Size             | Product purchase patterns    |
| Low Stock Alerts        | Inventory risk tracking      |
| Delayed Purchase Orders | Supply chain monitoring      |
| Fulfillment Rate        | Operational efficiency       |
| Category Sales          | Demand analysis              |
| Store Revenue           | Store performance comparison |

---

# 🔍 9. Major Business Insights

### 📌 Sales Insights

* Evening shopping behavior dominated order activity
* Fast-moving FMCG categories generated highest revenue
* Monthly revenue remained consistently strong

### 📌 Inventory Insights

* Several products experienced recurring low-stock situations
* Inventory pressure was concentrated in high-demand categories
* Inventory balancing opportunities existed across stores

### 📌 Fulfillment Insights

* Delayed purchase orders impacted delivery efficiency
* Partial fulfillment rates increased during high-demand periods
* Faster replenishment could improve customer satisfaction

---

# ⚠ 10. Challenges & Problem Solving

During development, several real-world data challenges were encountered and resolved:

### Challenges Faced

* Schema mismatches between SQL and CSV files
* Data consistency validation
* Large inventory dataset handling
* Dashboard optimization
* Relationship modeling complexity

### Solutions Implemented

* Schema corrections & standardization
* Column mapping validation
* Optimized Power BI relationships
* KPI refinement using DAX
* Improved data cleaning workflows

---

# 🚀 Future Enhancements

Future versions of StockPulse can include:

* Machine Learning demand forecasting
* Real-time inventory monitoring
* Supplier performance analytics
* Automated reorder recommendations
* Customer segmentation analysis
* Cloud-based deployment
* Predictive replenishment systems

---

# 📚 Key Learnings

This project strengthened practical skills in:

* SQL analytics
* Business Intelligence
* Data storytelling
* Dashboard design
* Retail analytics
* Inventory intelligence
* KPI development
* Data validation techniques

---

# 📷 Dashboard Preview

## Executive Dashboard

<img width="959" height="541" alt="StockPulse Overview Dashboard" src="https://github.com/user-attachments/assets/7f63a6d4-ade5-4ada-83d9-6c3cf9d5d318" />


---

## Sales & Demand Dashboard

<img width="956" height="540" alt="Sales Analysis" src="https://github.com/user-attachments/assets/bd91dbba-6586-428b-94f3-42583740697d" />


---

## Inventory & Fulfillment Dashboard

<img width="956" height="541" alt="Inventory Analysis" src="https://github.com/user-attachments/assets/24bd450e-76f7-432f-8671-2bb45487a7c7" />


---

# ▶ Running the Project

## Step 1 — Clone Repository

```bash
git clone <repository-url>
```

## Step 2 — Import Database Schema

Run SQL scripts from the `sql/` directory.

## Step 3 — Load CSV Datasets

Import all datasets into the configured database.

## Step 4 — Open Power BI File

```bash
StockPulse_Dashboard.pbix
```

Refresh data sources if required.

---

# 👨‍💻 Author

## Irfan Pathan

Aspiring Data Analyst passionate about:

* Business Intelligence
* SQL Analytics
* Power BI Dashboards
* Data Visualization
* Retail & Inventory Analytics

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub and sharing your feedback.
