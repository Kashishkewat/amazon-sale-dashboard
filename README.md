# 🛒 Amazon Sales Analysis Dashboard | Power BI

## 📊 Project Overview

This project is an **amazon Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard provides a comprehensive view of e-commerce business performance by analyzing **sales, customers, products, orders, quantity, payment methods, categories, cities, and order status**.

The main objective of this project is to transform raw e-commerce data into meaningful and interactive business insights using **Power Query, DAX, data modeling, and Power BI visualizations**.

---

## 🎯 Project Objectives

The dashboard was designed to answer important business questions such as:

- What is the total sales generated?
- How many customers and products are there?
- What is the total quantity sold?
- What is the average order value?
- How are sales changing month by month?
- Which cities generate the highest sales?
- Which products are the top sellers?
- Which product categories contribute the most to sales?
- Which payment methods are most commonly used?
- What is the distribution of order statuses?
- How does performance change based on year, brand, category, payment method, and order status?

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Excel / CSV Dataset**

---

## 📌 Key KPIs

The dashboard includes the following major KPIs:

| KPI | Value |
|---|---:|
| 👥 Total Customers | 17K |
| 📦 Total Products | 50 |
| 💰 Total Sales | 18.53M |
| 🛍️ Total Quantity | 60K |
| 📊 Average Order Value | 923.45 |

---

## 📈 Dashboard Features

### 1. Sales Trend Analysis

A monthly sales trend visual is used to understand how sales change throughout the year.

**Visual:** Line & Area Chart

It helps identify:

- Monthly sales performance
- High and low sales periods
- Sales fluctuations throughout the year

---

### 2. Sales by City

A geographic visualization shows sales distribution across different cities.

**Visual:** Map

Cities such as:

- Seattle
- Los Angeles
- San Francisco
- Denver
- Chicago
- New York
- Dallas
- Houston
- Philadelphia

can be analyzed based on sales performance.

---

### 3. Top Products by Sales

A horizontal bar chart displays the top-performing products based on sales.

**Visual:** Bar Chart

Example products appearing among the top performers include:

- Mechanical Keyboard
- Electric Kettle
- Microphone
- Wireless Earbuds
- Instant Pot
- Desk Organizer
- Memory Card
- Laptop Sleeve
- Air Fryer
- Phone Tripod

---

### 4. Sales by Payment Method

The dashboard analyzes sales distribution across different payment methods.

**Visual:** Donut Chart

Payment methods include:

- Credit Card
- Debit Card
- UPI
- Amazon Pay
- Net Banking
- Cash on Delivery

---

### 5. Orders by Order Status

The dashboard provides an overview of order fulfillment status.

**Visual:** Column Chart

Order statuses include:

- Delivered
- Shipped
- Pending
- Returned
- Cancelled

This helps understand the overall order lifecycle.

---

### 6. Sales by Category

A horizontal bar chart compares sales across different product categories.

Categories include:

- Electronics
- Home & Kitchen
- Clothing
- Books
- Toys & Games
- Sports & Outdoors

---

## 🎛️ Interactive Filters

The dashboard includes interactive slicers that allow users to analyze the data dynamically.

### Available Filters

- 📅 Year
- 🏷️ Brand
- 📂 Category
- 💳 Payment Method
- 📦 Order Status

Users can combine multiple filters to explore specific segments of the business.

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query** before creating the dashboard.

The data preparation process included:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Formatting dates
- Cleaning categorical fields
- Creating required columns
- Preparing data for analysis

---

## 🧮 Data Analysis & DAX

DAX measures were created to calculate important business KPIs such as:

```DAX
Total Sales =
SUM(Sales[SalesAmount])

Total Quantity =
SUM(Sales[Quantity])

Total Customers =
DISTINCTCOUNT(Sales[CustomerID])

Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders]
)
Dashboard Structure
E-Commerce Sales Dashboard
│
├── KPI Cards
│   ├── Total Customers
│   ├── Total Products
│   ├── Total Sales
│   ├── Total Quantity
│   └── Average Order Value
│
├── Sales Analysis
│   ├── Monthly Sales
│   ├── Sales by City
│   ├── Sales by Product
│   └── Sales by Category
│
├── Order Analysis
│   ├── Orders by Status
│   └── Payment Method Analysis
│
└── Interactive Filters
    ├── Year
    ├── Brand
    ├── Category
    ├── Payment Method
    └── Order Status
📷 Dashboard Preview

💡 Key Insights

The dashboard enables users to identify:

Overall e-commerce sales performance
Monthly sales trends
High-performing products
High-performing categories
Geographic sales distribution
Payment method preferences
Order fulfillment patterns
Customer and product volume
Average order value
🚀 Skills Demonstrated

Through this project, I practiced:

Power BI Dashboard Development
Power Query
DAX
Data Cleaning
Data Transformation
Data Modeling
KPI Development
Data Visualization
Interactive Slicers
Business Intelligence
Exploratory Data Analysis

## 📷 Screenshot / Demo

Here is what the dashboard looks like:

![Amazon Sales Dashboard](https://github.com/Kashishkewat/amazon-sale-dashboard/blob/main/amazon%20sale%20dashboard.png?raw=true)
