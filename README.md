# E-Commerce Sales Analysis using Python

## Project Overview

This project focuses on analyzing an E-Commerce (DataCo) dataset using Python to extract meaningful business insights from raw sales data. The analysis includes data cleaning, exploratory data analysis (EDA), trend identification, and visualization to understand customer behavior, sales performance, and profitability.

The objective of this project is to transform raw business data into actionable insights that can support decision-making.

---

## Dataset Information

* Dataset: DataCo E-Commerce Dataset
* Total Records: 115,000+ rows
* Features: Customer information, product details, sales, profit, order details, regions, categories, and dates

Main columns used:

* Category Name
* Sales
* Profit Per Order
* Customer Segment
* Order Region
* Product Price
* Order Quantity
* Order Date

---

## Project Objectives

The analysis was performed to answer business questions such as:

* Which product categories generate the highest sales?
* Which categories produce the highest profit?
* Which regions contribute the most revenue?
* What are the monthly sales trends?
* Who are the top customers?
* Which products or categories are causing losses?
* Is there any relationship between price and quantity sold?
* Are there any outliers in sales data?

---

## Data Cleaning & Preprocessing

Steps performed during preprocessing:

* Loaded dataset using Pandas
* Examined dataset structure and data types
* Removed duplicate values
* Handled missing values
* Converted date columns into datetime format
* Created new features:

  * Year
  * Month
  * Day

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### Sales Analysis

* Category-wise sales analysis
* Region-wise sales analysis
* Customer segment analysis

### Profit Analysis

* Profit by category
* Loss-making products and categories

### Trend Analysis

* Monthly sales trends
* Revenue pattern analysis

### Customer Analysis

* Top customers by revenue
* Customer purchase behavior

### Outlier Detection

* Sales distribution
* Extreme order identification

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Feature Engineering
* Python for Data Analytics

---

## Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── data/
│   └── Dataco.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── presentation/
│   └── linkedin_project_presentation.pptx
│
├── images/
│   ├── sales_analysis.png
│   ├── profit_analysis.png
│   └── monthly_trend.png
│
├── README.md
└── requirements.txt
```

## Future Improvements

* Build interactive dashboards using Power BI or Tableau
* Create predictive models for sales forecasting
* Perform customer segmentation analysis
* Develop recommendation systems

---

## Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize business data for extracting meaningful insights. The analysis helps identify sales trends, customer patterns, and revenue opportunities that can support business decision-making.

---
If you found this project useful, feel free to star the repository.
