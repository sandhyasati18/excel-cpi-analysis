# 📊 All India Consumer Price Index (CPI) Analysis

## 📌 Project Overview

This project analyzes **India's Consumer Price Index (CPI)** data using Microsoft Excel to understand inflation patterns, category-wise price movements, and changes in CPI over time.

The project demonstrates an end-to-end Excel analysis workflow including **data cleaning, Excel formulas, Pivot Tables, Pivot Charts, conditional formatting, correlation analysis, and dashboard creation**.

The main objective was to convert raw CPI data into meaningful insights that make inflation trends easier to understand and compare.

---

## 🎯 Project Objectives

The analysis was designed to answer key questions such as:

* Which year recorded the highest Year-over-Year (YoY) inflation?
* How has CPI changed over the years?
* Which expenditure categories contribute most to the CPI basket?
* How does food inflation change month over month?
* How do Rural and Urban CPI values compare?
* Which categories show the strongest relationship with crude oil prices?
* What are the major inflation trends visible in the dataset?

---

## 🛠️ Tools & Excel Skills Used

**Tool:** Microsoft Excel

**Techniques Used:**

* Data Cleaning
* Pivot Tables
* Pivot Charts
* Excel Dashboard
* Conditional Formatting
* Sorting & Filtering
* Data Aggregation
* Year-over-Year (YoY) Analysis
* Month-over-Month (MoM) Analysis
* Correlation Analysis

### Excel Functions

`MAXIFS()` | `MINIFS()` | `IFERROR()` | `COUNTIFS()` | `SUMPRODUCT()` | `CORREL()`

---

## 📂 Dataset

The dataset contains **All India Consumer Price Index data** across multiple years and expenditure categories.

Major categories analyzed include:

* Food & Beverages
* Clothing & Footwear
* Housing
* Health
* Education
* Transportation
* Dairy
* Other expenditure categories

The analysis also considers **Rural, Urban, and combined CPI values** where applicable.

---

## 🔍 Analysis Performed

### 1. Year-over-Year Inflation Analysis

Calculated YoY changes to understand how CPI changed compared with the previous year.

**Calculation:**

`YoY % = (Current Year CPI - Previous Year CPI) / Previous Year CPI × 100`

This helped identify periods where inflation increased most significantly.

---

### 2. Month-over-Month Food Inflation

Analyzed monthly changes in the **Food & Beverages** category to understand short-term movements in food prices.

This analysis helped identify months experiencing relatively stronger increases or decreases in food inflation.

---

### 3. CPI Basket Contribution

Compared expenditure categories to understand their relative contribution to the overall CPI basket.

The analysis showed that **Food & Beverages represented the largest contribution among the analyzed categories**.

---

### 4. Rural vs Urban Analysis

Compared CPI values across Rural and Urban sectors to understand differences in consumer price movements.

Excel functions and Pivot Tables were used to filter and summarize CPI values by sector, year, month, and category.

---

### 5. Highest Inflation Year

Year-wise CPI analysis was performed to identify the period with the strongest inflationary movement.

**Key Finding:**
**2022 recorded the highest YoY inflation** in the analysis.

---

### 6. Crude Oil Correlation Analysis

Correlation analysis was performed for **2021–2023** to examine the relationship between imported crude oil prices and selected CPI categories.

The analysis produced the following correlations:

| CPI Category   | Correlation |
| -------------- | ----------: |
| Fuel           |  **0.9297** |
| Transportation |  **0.8922** |
| Food           |  **0.8514** |

The results indicate a strong positive relationship between crude oil price movements and these categories during the analyzed period.

> Correlation indicates association and should not by itself be interpreted as proof of causation.

---

## 📈 Key Insights

* **2022** showed the highest YoY inflation in the analyzed period.
* **Food & Beverages** represented the largest contribution among the analyzed CPI categories.
* CPI patterns varied between Rural and Urban segments.
* Fuel showed the strongest correlation with imported crude oil prices during the 2021–2023 analysis.
* Transportation also demonstrated a strong positive relationship with crude oil price movements.
* Pivot Tables and charts helped identify category-level and time-based inflation patterns more clearly.

---

## 📊 Excel Dashboard

An interactive Excel dashboard was developed to summarize the CPI analysis visually.

The dashboard uses:

* Pivot Tables
* Pivot Charts
* Slicers
* KPI summaries
* Category comparisons
* Inflation trend visualizations

The dashboard allows the analysis to be explored across different categories and periods without manually filtering the raw dataset.

---

## 📁 Repository Structure

excel-cpi-analysis/
│
├── Screenshots/
├── excel/
└── README.md

---

## 💡 Skills Demonstrated

Through this project, I demonstrated the ability to:

* Clean and organize real-world datasets in Excel
* Apply Excel formulas to solve analytical questions
* Create and interpret Pivot Tables
* Calculate YoY and MoM changes
* Perform correlation analysis using `CORREL()`
* Build interactive Excel dashboards
* Identify trends and patterns from economic data
* Convert raw data into meaningful analytical insights
* Communicate findings through charts and visualizations

---

## 🎯 Business / Analytical Value

CPI analysis can help analysts understand how prices change across different categories and periods.

This project demonstrates how Excel can be used to transform economic data into a structured analysis that supports:

* Inflation monitoring
* Category-level price analysis
* Trend identification
* Rural vs Urban comparisons
* Economic reporting
* Data-driven decision-making

---


This project is part of my Data Analytics portfolio and demonstrates practical application of Microsoft Excel for data cleaning, analysis, visualization, and insight generation.
