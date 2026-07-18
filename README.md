# 📊 SQL Data Warehouse Project

## 📌 Project Overview

This project demonstrates the design and implementation of a modern SQL Data Warehouse using the Medallion Architecture (Bronze, Silver, Gold). The solution integrates data from multiple source systems, performs data cleansing and transformation through ETL pipelines, and delivers business-ready analytical datasets.

The project also includes advanced SQL analytics to generate business insights for decision-making.

---

# 🏗️ Data Warehouse Architecture

The project follows the Medallion Architecture:

```
Source Systems
      │
      ▼
 Bronze Layer
      │
      ▼
 Silver Layer
      │
      ▼
  Gold Layer
      │
      ▼
Business Analysis
```

### Bronze Layer
- Load raw data from source systems.
- Preserve original data without transformations.
- Acts as the staging layer.

### Silver Layer
- Clean data.
- Remove duplicates.
- Handle missing values.
- Standardize data formats.
- Prepare data for analysis.

### Gold Layer
- Create Fact and Dimension tables.
- Build the Star Schema.
- Provide business-ready datasets.

---

# ⚙️ ETL Process

The ETL pipeline includes:

- Extract data from CRM & ERP source systems.
- Load raw data into Bronze Layer.
- Clean and transform data into Silver Layer.
- Build analytical models in Gold Layer.
- Execute business analytical queries.

---

# 📂 Project Structure

```
SQL-Data-Warehouse-Project
│
├── datasets/
│
├── scripts/
│   ├── Bronze
│   ├── Silver
│   └── Gold
│
├── analysis/
│   ├── Business Analysis.sql
│   ├── Customer Segmentation.sql
│   ├── Product Analysis.sql
│   └── Sales Analysis.sql
│
├── README.md
│
└── LICENSE
```

---

# 🛠️ Technologies Used

- SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- Git
- GitHub
- Data Warehouse
- ETL
- Medallion Architecture

---

# 📊 Business Analysis

The Gold Layer was analyzed using advanced SQL queries to answer real business questions.

---

## 📅 Monthly Sales Performance

### Objective

Analyze sales performance across months and years.

### Metrics

- Total Sales
- Average Product Price
- Total Quantity Sold
- Number of Customers

### SQL Concepts

- GROUP BY
- YEAR()
- DATENAME()
- Aggregate Functions

---

## 📈 Running Total & Moving Average

### Objective

Track long-term business performance.

### Metrics

- Running Total Sales
- Moving Average Price

### SQL Concepts

- Window Functions
- SUM() OVER()
- AVG() OVER()

---

## 📦 Year-over-Year Product Performance

### Objective

Compare product sales across different years.

### Metrics

- Current Year Sales
- Previous Year Sales
- Average Sales
- Difference from Average
- Year-over-Year Growth

### SQL Concepts

- CTE
- LAG()
- AVG() OVER()
- PARTITION BY
- CASE

---

## 🛒 Product Category Analysis

### Objective

Measure each category's contribution to overall business performance.

### Metrics

- Total Sales
- Total Quantity
- Sales Contribution %
- Quantity Contribution %

### SQL Concepts

- Window Functions
- Percentage Calculations
- SUM() OVER()

---

## 💰 Product Cost Segmentation

### Objective

Group products based on cost ranges.

### Segments

- Below 100
- 100 - 500
- 500 - 1000
- Above 1000

### SQL Concepts

- CASE
- GROUP BY

---

## 👥 Customer Segmentation

### Objective

Segment customers according to their spending behavior.

### Customer Types

- VIP
- Regular
- New

### Metrics

- Total Spending
- Customer Lifespan
- First Purchase
- Last Purchase

### SQL Concepts

- CTE
- CASE
- DATEDIFF()
- Aggregate Functions

---

# 🧠 SQL Skills Demonstrated

- Data Warehouse Design
- ETL Pipeline Development
- Data Cleaning
- Data Transformation
- Data Validation
- Data Standardization
- Window Functions
- Aggregate Functions
- CTE (Common Table Expressions)
- CASE Statements
- JOIN Operations
- Customer Segmentation
- Product Segmentation
- Time-Series Analysis
- Running Totals
- Moving Averages
- Year-over-Year Analysis

---

# 📈 Business Questions Answered

This project provides answers to important business questions such as:

- How do sales perform over time?
- Which products generate the highest revenue?
- Which product categories contribute the most sales?
- What percentage does each category contribute?
- Which customers are VIP customers?
- How long do customers stay active?
- How does each product perform compared to its historical average?
- Which products are increasing or decreasing year-over-year?
- How are products distributed across different price ranges?

---

# ⭐ Project Highlights

- Designed a complete SQL Data Warehouse using the Medallion Architecture.
- Built a multi-layer ETL pipeline (Bronze → Silver → Gold).
- Developed Stored Procedures for automated data loading.
- Cleaned, validated, and standardized data from multiple source systems.
- Removed duplicate records using Window Functions.
- Applied business rules for data transformation.
- Implemented Slowly Changing Dimension (SCD Type 2).
- Created Fact and Dimension tables using Star Schema.
- Performed advanced SQL analytics using CTEs and Window Functions.
- Built customer segmentation and product segmentation models.
- Conducted Year-over-Year and trend analysis.
- Generated business insights to support decision-making.


---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

- Data Warehouse Architecture
- ETL Design
- Data Modeling
- Star Schema
- SQL Performance Optimization
- Business Analytics
- Data Cleaning
- Data Transformation
- Window Functions
- Analytical SQL
- Customer Analytics
- Product Analytics

---

# 👩‍💻 Author

**Mona Hosni Ibrahim Salamah**

Aspiring Data Engineer | SQL | Data Warehousing | ETL | Power BI | Python
