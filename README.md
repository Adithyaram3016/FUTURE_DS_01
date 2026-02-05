# 🚗 Car Sales Performance Analytics Dashboard (Power BI)

## 📌 Task Overview

As part of the **Future Interns – Data Science & Analytics Internship (Task 1)**, this task focuses on performing **Business Sales Performance Analytics** using a car sales dataset and building an interactive dashboard in Power BI.

The purpose of this task was to analyze sales data in a way that answers important business questions such as:

* Which car models generate the most revenue?
* Which manufacturers dominate sales performance?
* Do customers prefer expensive cars or affordable cars?
* Which vehicle types contribute the most to revenue?

This task reflects how data analysts work with business data to extract meaningful insights for decision-making.

---

## 🗂️ Dataset Description

The dataset contains car model details along with sales and pricing information. Key columns used in the analysis:

* Manufacturer
* Model
* Vehicle_type
* Sales_in_thousands
* Price_in_thousands
* Latest_Launch

The dataset did not contain a direct Revenue column, so revenue was derived during the analysis.

---

## 🧹 Data Cleaning & Preparation

Data cleaning was performed using **Power Query** in Power BI:

* Corrected data types for date and numeric columns
* Removed rows with invalid or missing dates
* Removed rows with missing price values to avoid incorrect revenue calculations
* Created a new **Revenue** column using:

  ```
  Revenue = Sales_in_thousands × Price_in_thousands
  ```

This ensured accurate and meaningful analysis.

---

## 📊 Dashboard Components

The dashboard includes the following visuals:

* **KPI Cards**

  * Total Revenue
  * Total Units Sold
  * Number of Models
  * Number of Manufacturers

* **Top 10 Revenue Generating Car Models**

* **Revenue Contribution by Manufacturer**

* **Vehicle Type Contribution to Total Revenue**

* **Price vs Sales Analysis**

* **Interactive Slicers** for Manufacturer and Vehicle Type

---

## 🔍 Key Insights from Analysis

### 🚘 Top Models

A small group of car models contributes a major portion of total revenue, indicating that focusing on these models can significantly improve business performance.

### 🏭 Manufacturer Performance

Certain manufacturers clearly dominate revenue generation, showing strong brand demand and customer preference.

### 🚗 Vehicle Type Contribution

Passenger vehicles contribute more to overall revenue compared to basic car types, indicating preference for larger, feature-rich vehicles.

### 💰 Price vs Sales Relationship

Affordable cars sell in higher volumes, while premium cars sell in lower quantities but still contribute significantly to revenue. This shows the importance of both budget and premium segments.

---

## 🛠️ Tools Used

* Power BI (Data cleaning, visualization, dashboard creation)
* Power Query (Data preparation)

---

## 🎯 Learning Outcomes

Through this task, I learned:

* Importing and preparing CSV data in Power BI
* Handling missing values and data errors
* Creating KPIs and calculated columns
* Choosing appropriate chart types for business questions
* Designing a clean, interactive dashboard
* Understanding how analytics translates data into business insights

---

## 📎 Conclusion

This task demonstrates how raw sales data can be transformed into actionable business insights using Power BI and highlights the role of analytics in understanding product performance and revenue drivers.
