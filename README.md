# 📊 AdventureWorks Sales Dashboard (Power BI)

## 🧠 Project Summary

This project focuses on analyzing the **AdventureWorks sales dataset** to extract meaningful business insights using **Power BI**. The dashboard provides a complete view of revenue trends, customer behavior, product performance, and return analysis.

The goal of this project is to convert raw data into **interactive dashboards** that help businesses make **data-driven decisions**.

---

## 🎯 Business Objectives

- 📈 Analyze overall sales performance across regions
- 🏆 Identify top-performing products and categories
- 💰 Track revenue and profit trends over time
- 👥 Understand customer purchasing behavior
- 🔄 Monitor product return rates

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** - Dashboard creation and visualization
- **DAX (Data Analysis Expressions)** - Custom measures and calculations
- **Power Query** - Data cleaning & transformation
- **Data Modeling** - Establishing relationships between tables

---

## 📊 Dataset

This project uses the **AdventureWorks** sales dataset, which includes multiple tables with comprehensive business data.

### 📁 Dataset Files:

The dataset consists of the following tables:

- **Calendar.csv** - Date dimension table (2020-2022)
- **Customer.csv** - Customer demographics and information
- **Product.csv** - Product details and specifications
- **Product_Categories.csv** - Product category mapping
- **Product_Subcategories.csv** - Subcategory details
- **Sales_Data_2020.csv** - Sales transactions for 2020
- **Sales_Data_2021.csv** - Sales transactions for 2021
- **Sales_Data_2022.csv** - Sales transactions for 2022
- **Territory.csv** - Geographic and regional data
- **Returns.csv** - Product return information

### 📥 Download Dataset:

You can download the complete dataset from:

**Option 1:**  [Download from Kaggle - AdventureWorks Dataset](https://www.kaggle.com/datasets/ukveteran/adventure-works)

**Option 2:** Available in the `data/` folder of this repository

### 📊 Dataset Statistics:

- **Total Records**: 60,000+ sales transactions
- **Time Period**: 2020-2022
- **Geographic Coverage**: 6 countries (Australia, Canada, France, Germany, UK, USA)
- **Product Categories**: Accessories, Bikes, Clothing
- **Customer Records**: Multiple demographics including education and occupation data

---

## 🔄 Data Preparation Steps

✅ Removed null and duplicate values  
✅ Created relationships between multiple tables  
✅ Standardized data formats  
✅ Built calculated columns and DAX measures  
✅ Applied data transformation using Power Query  
✅ Established star schema data model

---

## 📊 Dashboard Overview

### 🔹 Page 1: Sales Performance Overview



![Sales Dashboard](images/page1.jpg)



**Key Metrics:**
- **Total Revenue**: 24.91M
- **Total Profit**: 10.46M
- **Total Return**: 1,828 orders
- **Return Percentage**: 2.17%
- **Order Quantity**: 84K units

**Visualizations:**
- 📈 Weekly Revenue and Profit trends (2019-2022)
- 📊 Order distribution by Categories (Accessories, Bikes, Clothing)
- 💵 Monthly Revenue: 1.83M (↑3.31% from previous month)
- 🏆 Most Profitable Subcategory: Tires and Tubes
- 💰 Most Revenue Subcategory: Road Bikes

---

### 🔹 Page 2: Customer & Geographic Insights



![Demographics Dashboard](images/page2.jpg)



**Order Quantity by Education Level:**
- Bachelors: 29.65%
- Graduate Degree: 27.49%
- Partial College: 17.38%
- High School: 8.15%
- Partial High School: 17.33%

**Order Quantity by Occupation:**
- Professional: 31.83%
- Skilled Manual: 23.57%
- Management: 17.45%
- Clerical: 15.55%
- Manual: 11.87%

**Geographic Distribution:**
- Australia, Canada, France, Germany, United Kingdom, United States

---

## 📈 Key Insights

**Revenue & Profitability:**
- Total revenue reached 24.91M, showing strong business growth
- Bikes category generated the highest revenue (approximately 60%)
- Road Bikes is the top-performing subcategory
- Profit margin maintained at 42% (10.46M profit on 24.91M revenue)

**Product Performance:**
- Accessories have the highest order volume
- Tires and Tubes are the most profitable subcategory
- Return rate maintained at a healthy 2.17%

**Customer Behavior:**
- Bachelors degree holders contribute to 29.65% of orders
- Professional occupation leads in purchasing (31.83%)
- Clear seasonal trends with peak demand periods

**Geographic Performance:**
- Strong presence across 6 major countries
- North America and Europe are primary markets

---

## 💡 Dashboard Features

✅ Interactive filters (Continent, Country, Month)  
✅ Drill-down functionality for deeper insights  
✅ Dynamic KPI cards with real-time updates  
✅ Clean and intuitive UI design  
✅ Time-based analysis with trend comparisons

---

## 📌 Business Impact

- Helps identify high-performing products and regions
- Supports better pricing and marketing strategies
- Enables data-driven decision making
- Helps reduce return rates through product analysis
- Improves inventory management based on demand patterns

---

## 📎 Future Improvements

- Add sales forecasting using time series models
- Integrate real-time data sources via Power BI Service
- Implement advanced customer segmentation techniques
- Add predictive analytics for inventory management

---

**Project Status**: ✅ Completed  
**Last Updated**: March 2026
