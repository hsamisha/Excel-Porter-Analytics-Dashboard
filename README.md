# 🚚 Porter Analytics – Food Delivery Data Analysis

##  Project Overview

**Porter Analytics** is an Excel-based data analysis project focused on understanding food delivery operations and order patterns.

The project analyzes order information, delivery times, restaurant categories, item quantities, order values, delivery partners, and operational conditions to identify meaningful patterns and insights.

The analysis is performed using **Microsoft Excel** with data cleaning, calculations, Pivot Tables, and an interactive dashboard.



##  Project Objectives

The main objectives of this project are:

* Analyze food delivery orders.
* Understand order volume and order patterns.
* Analyze delivery duration.
* Identify popular restaurant categories.
* Analyze the number of items per order.
* Analyze order value and subtotal.
* Study delivery partner availability.
* Examine busy and outstanding delivery partners.
* Analyze delivery performance across different time periods.
* Identify patterns in order and delivery operations.
* Present key insights through an Excel dashboard.



## Dataset

The project uses food delivery order data containing information related to orders, stores, restaurants, delivery partners, and delivery times.

### Important Fields

| Field                        | Description                          |
| ---------------------------- | ------------------------------------ |
| **market_id**                | Identifier for the market            |
| **created_at**               | Order creation date and time         |
| **actual_delivery_time**     | Actual delivery date and time        |
| **store_id**                 | Store identifier                     |
| **store_primary_category**   | Primary category of the store        |
| **order_protocol**           | Order protocol used                  |
| **total_items**              | Total number of items in the order   |
| **subtotal**                 | Order subtotal                       |
| **num_distinct_items**       | Number of distinct items             |
| **min_item_price**           | Minimum item price                   |
| **max_item_price**           | Maximum item price                   |
| **total_onshift_partners**   | Delivery partners currently on shift |
| **total_busy_partners**      | Busy delivery partners               |
| **total_outstanding_orders** | Outstanding orders                   |



##  Tools Used

* **Microsoft Excel**
* Excel Tables
* Excel Formulas
* Pivot Tables
* Pivot Charts
* Slicers
* Data Cleaning
* Data Transformation
* Dashboard Development
* Data Visualization



##  Project Workflow


Raw Data
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Feature Creation
   ↓
Calculations
   ↓
Pivot Table Analysis
   ↓
Data Visualization
   ↓
Dashboard Development
   ↓

##  Data Cleaning & Transformation

The project includes a separate **Clean** sheet for preparing the raw dataset for analysis.

The data preparation process includes:

* Organizing raw order data.
* Standardizing date and time information.
* Preparing delivery duration information.
* Organizing restaurant categories.
* Preparing quantity-related fields.
* Creating date-related fields.
* Creating time-related fields.
* Creating day and month classifications.
* Preparing data for Pivot Table analysis.



##  Feature Engineering

Additional analytical fields were created to support the analysis.

###  Date

The order creation date is extracted and organized for time-based analysis.

###  Time

Order creation time is separated for analyzing ordering patterns.

###  Day Name

The day of the week is derived from the order date.

###  Month Name

The month is extracted for monthly order analysis.

###  Quarter

Quarter information is created to support quarterly analysis.

###  Duration Minutes

Delivery duration is represented in minutes to analyze delivery performance.

###  Quantity Size

Orders can be grouped based on quantity to understand order-size patterns.

---

##  Key Analysis Areas

### 1.  Order Analysis

The project analyzes:

* Total orders
* Total items
* Distinct items per order
* Order subtotal
* Minimum item price
* Maximum item price
* Order quantity



### 2.  Restaurant Category Analysis

The project examines:

* Store categories
* Number of orders by category
* Popular food categories
* Category-level order patterns

Examples of categories represented in the dataset include:

* American
* Mexican
* Indian
* Italian
* Sandwich
* Thai
* Cafe
* Salad
* Pizza
* Chinese
* Burger
* Breakfast
* Mediterranean
* Japanese
* Greek


### 3.  Delivery Performance Analysis

The project analyzes:

* Delivery duration
* Average delivery duration
* Delivery performance
* Order timing
* Delivery partner availability

The **Duration minutes** field is used to measure delivery time.



### 4. Delivery Partner Analysis

The dataset contains operational information about delivery partners, including:

* Total on-shift partners
* Total busy partners
* Total outstanding orders

This helps analyze delivery capacity and operational workload.



### 5.  Order Value Analysis

The project analyzes:

* Order subtotal
* Minimum item price
* Maximum item price
* Total items
* Number of distinct items

This provides insight into customer order size and order value.



## Dashboard

The project includes a dedicated **Dashboard** sheet for presenting important analytical results.

The dashboard is designed to provide a quick overview of:

* Order volume
* Delivery performance
* Restaurant categories
* Order quantities
* Order value
* Delivery partner activity

Interactive Excel features such as **Pivot Charts and Slicers** can be used to explore the data.



##  Important Metrics

The analysis focuses on metrics such as:

| Metric                        | Purpose                             |
| ----------------------------- | ----------------------------------- |
| **Total Orders**              | Measures overall order volume       |
| **Total Items**               | Measures items ordered              |
| **Average Delivery Duration** | Measures delivery performance       |
| **Average Order Value**       | Measures typical order value        |
| **Distinct Items**            | Measures product variety            |
| **Busy Partners**             | Measures delivery workload          |
| **Outstanding Orders**        | Measures pending operational demand |
| **Orders by Category**        | Measures category popularity        |



##  Key Questions Answered

The project helps answer questions such as:

* How many orders are placed?
* Which restaurant categories receive the most orders?
* What is the average delivery duration?
* How does order quantity vary?
* What is the average order value?
* Which categories have larger order volumes?
* How many delivery partners are available?
* How many partners are busy?
* How many orders remain outstanding?
* How does delivery duration vary over time?
* Which days or months show higher order activity?
* What patterns exist between order size and delivery performance?



## 📁 Project Structure


Porter-Analytics-Excel-Project/
│
├── Porter_Analytics_excel_project3.xlsx
│
├── README.md
│
└── Dashboard/
    └── Porter Analytics Dashboard


### Excel Workbook Structure


Porter_Analytics_excel_project3.xlsx
│
├── RAW
│   └── Original food delivery dataset
│
├── Clean
│   └── Cleaned and transformed dataset
│
├── Calculations
│   └── Analytical calculations and Pivot Table summaries
│
└── Dashboard
    └── Interactive analytics dashboard


##  How to Use the Project

### Step 1: Open the Excel Workbook

Open:

```text
Porter_Analytics_excel_project3.xlsx
```

### Step 2: Explore the Raw Data

Open the **RAW** sheet to view the original dataset.

### Step 3: Review the Cleaned Data

Open the **Clean** sheet to view the prepared dataset.

### Step 4: Review Calculations

Open the **Calculations** sheet to explore analytical calculations and summaries.

### Step 5: View the Dashboard

Open the **Dashboard** sheet to explore the visual analysis.

### Step 6: Interact With the Dashboard

Use available:

* Slicers
* Pivot Tables
* Pivot Charts
* Filters

to explore different order and delivery patterns.



## Conclusion

The **Porter Analytics – Food Delivery Data Analysis** project demonstrates how Microsoft Excel can be used to transform raw food delivery data into meaningful operational insights.

The project covers **data cleaning, transformation, order analysis, restaurant category analysis, delivery performance, delivery partner activity, order value analysis, Pivot Table analysis, and dashboard development**.

This project demonstrates practical skills in **Excel-based data analysis, data visualization, dashboard development, and business-oriented data interpretation**.



## Author

### **Amisha**

**M.Tech – Computer Science Engineering**
**Aspiring Data Analyst**

### Skills Demonstrated


Microsoft Excel
Data Cleaning
Data Transformation
Data Analysis
Pivot Tables
Pivot Charts
Slicers
Data Visualization
Dashboard Development
Business Analytics

## ⭐ Project Highlights

* 🚚 Food Delivery Analytics
* 📊 Excel Dashboard
* 🛍️ Order Analysis
* 🍽️ Restaurant Category Analysis
* ⏱️ Delivery Duration Analysis
* 👨‍🚚 Delivery Partner Analysis
* 💰 Order Value Analysis
* 📈 Pivot Table Analysis
* 🎛️ Interactive Slicers
* 🔍 Operational Insights


