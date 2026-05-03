# 📊 Food Delivery Analytics Dashboard (Power BI)

## 🔹 Project Overview

This project presents an end-to-end Business Intelligence solution built using Power BI to analyze food delivery operations, customer behavior, and restaurant performance. The dashboard provides actionable insights across multiple dimensions such as revenue, delivery efficiency, customer retention, and restaurant analytics.

---

## 🔹 Dataset Description

The dataset consists of multiple tables capturing:

* **Orders**: Order details, delivery time, order value, status
* **Customers**: Customer segmentation and behavior
* **Restaurants**: Cuisine, rating, cost bucket, location
* **Date Table**: Time-based analysis (YTD, trends)

---

## 🔹 Data Cleaning & Transformation (Power Query)

* Removed duplicates and handled missing/null values
* Standardized column names and corrected data types
* Created derived columns:

  * Cost Bucket
  * Rating Bucket
  * City grouping
* Extracted date components (Year, Month, Quarter)
* Ensured consistent schema for modeling

---

## 🔹 Data Modeling

* Designed a star schema-like model
* Established relationships:

  * Orders ↔ Customers
  * Orders ↔ Restaurants
  * Orders ↔ Date Table
* Created separate measure tables for better organization:

  * KPI Measures
  * Customer Measures
  * Restaurant Measures
  * Status Measures
  * Time Intelligence Measures

---

## 🔹 DAX Measures

Developed key business metrics using DAX:

* **Revenue Metrics**: Total Revenue, Revenue per Restaurant
* **Customer Metrics**: Repeat Customers %, Orders per Customer
* **Operational Metrics**: Avg Delivery Time, Late Delivery %, Cancellation %
* **Time Intelligence**: Revenue YTD, Growth %, Previous Month Revenue
* **Dynamic KPI Selection** using slicer (`Selected KPI value`)

---

## 🔹 Dashboard Features

### 📌 Executive Overview

* High-level KPIs: Revenue, Orders, Delivery Time, AOV
* Revenue & Order trends
* Top performing cities and restaurants
* Order status breakdown

### 📌 Customer Analytics

* Total vs Repeat customers
* Customer retention metrics
* Signup trends over time
* New vs Returning customer distribution

### 📌 Restaurant Analytics

* Cuisine performance analysis
* Rating vs Revenue relationship
* Cost bucket distribution
* Top restaurants by revenue

### 📌 Delivery & Operations

* Delivery performance metrics
* Late deliveries and cancellations
* City-wise delivery efficiency
* Operational bottleneck identification

### 📌 Advanced Insights

* Dynamic KPI analysis using slicer
* Trend analysis based on selected KPI
* Multi-dimensional visual exploration

### 📌 Drillthrough (Restaurant Details)

* Detailed restaurant-level insights
* Revenue & order trends
* Customer type distribution
* Delivery performance breakdown

---

## 🔹 Key Insights

* Higher-rated restaurants tend to generate more revenue
* Premium cost bucket contributes significantly to revenue
* Certain cities show higher delivery delays indicating operational inefficiencies
* Repeat customers contribute a major share of total orders

---

## 🔹 Tools & Technologies

* Power BI
* Power Query (ETL)
* DAX (Data Analysis Expressions)

---
👤Shivam Parihari
Thank you for visiting❤️
