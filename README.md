# 🛒 EVA - E-Commerce Data Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data using Python and various data analysis and visualization libraries. The main objective is to transform raw transactional data into meaningful business insights.

The project involves data cleaning, preprocessing, data transformation, exploratory data analysis (EDA), and data visualization. Multiple datasets were integrated to analyze customer behavior, product performance, sales trends, revenue generation, payment preferences, and geographical performance.

## 🎯 Project Objectives

* Clean and preprocess raw e-commerce datasets.
* Integrate multiple datasets into a single analytical dataset.
* Perform exploratory data analysis (EDA).
* Analyze customer, product, sales, and revenue performance.
* Identify important trends and patterns using data visualization.
* Extract meaningful business insights from the data.

## 🛠️ Tools & Technologies

* **Python** – Primary programming language
* **Jupyter Notebook** – Interactive environment for analysis
* **Pandas** – Data cleaning, manipulation, merging, and analysis
* **NumPy** – Numerical computations and data processing
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical and advanced visualizations

## 📂 Dataset

The project uses four separate datasets:

### 1. Customers Dataset

Contains customer information such as:

* Customer ID
* Customer Name
* City
* Signup Date

### 2. Orders Dataset

Contains information about customer orders:

* Order ID
* Customer ID
* Order Date
* Payment Method

### 3. Order Items Dataset

Contains details about products included in each order:

* Order ID
* Product ID
* Quantity
* Unit Price

### 4. Products Dataset

Contains product information:

* Product ID
* Product Name
* Category
* Base Price

The datasets were connected using common identifiers such as Customer ID, Order ID, and Product ID.

## 🔄 Project Workflow

The project followed these major steps:

1. **Data Loading**
2. **Data Cleaning**
3. **Missing Value Treatment**
4. **Duplicate Record Removal**
5. **Data Type Conversion**
6. **Data Validation**
7. **Dataset Integration**
8. **Feature Creation**
9. **Exploratory Data Analysis**
10. **Data Visualization**
11. **Business Insights**

## 🧹 Data Cleaning & Transformation

The datasets were examined for missing values, duplicate records, incorrect data types, and inconsistencies.

Date columns such as Order Date and Signup Date were converted into datetime format. The datasets were then merged using their common identifiers to create a consolidated analytical dataset.
A new **Revenue** variable was created using:

**Revenue = Quantity × Unit Price**

Additional time-based features such as **Month, Year, and Day Name** were also created for time-based analysis.

## 📊 Analysis & Visualizations

The project includes analysis and visualizations covering:

* Revenue by Product Category
* Top 10 Revenue-Generating Products
* Monthly Revenue Trend
* Revenue by City
* Payment Method Analysis
* Top 10 Customers by Revenue
* Quantity Sold by Product Category
* Revenue Distribution

These visualizations were created using Matplotlib and Seaborn to make business trends and patterns easier to understand.

## 💡 Key Insights

Some of the key findings from the analysis include:

* Total revenue generated was **₹170,000,000**.
* **Wireless Mouse** was the highest revenue-generating product and the most sold product.
* **Smartphone** was the highest revenue-generating category.
* **Delhi** had the highest number of customers and contributed the highest revenue among cities.
* **UPI** was the most preferred payment method.
* **January** recorded the highest sales, while **August** recorded the lowest sales.
* A relatively small group of customers contributed a significant portion of total revenue.
* Revenue generation was concentrated among certain products and categories.

## 📁 Project Structure

```text
EVA-Python-Data-Analysis/
│
├── data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   └── products.csv
│
├── python/
│   └── eva_project.py
│
├── documentation/
│   └── EVA_Project_Documentation.docx
│
└── README.md
```

## 📄 Documentation

The complete project documentation contains detailed information about the dataset, data cleaning, transformation, exploratory data analysis, insights, visualizations, and conclusions.

## 🏁 Conclusion

This project demonstrates how Python can be used to transform raw e-commerce data into meaningful business intelligence. Through systematic data cleaning, transformation, exploratory analysis, and visualization, the project provides insights into customer behavior, product performance, revenue generation, sales trends, payment preferences, and geographical performance.

The analysis demonstrates the value of data-driven approaches for understanding business operations and identifying opportunities for improvement.
