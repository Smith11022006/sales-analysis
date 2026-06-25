# sales-analysis
Customer Sales Analysis - Data Analytics Project

# 📊 Customer Sales Analysis

A data analytics project analyzing 2823 sales transactions across 19 countries (2003–2005).

---

## 🎯 Objective
To analyze sales performance and identify key trends across products, regions, and time periods using Python and data visualization techniques.

---

## 🛠 Tools & Technologies
- **Python** — data loading and cleaning
- **Pandas** — data manipulation and analysis
- **Matplotlib** — data visualization
- **HTML & CSS** — project website
- **GitHub Pages** — deployment

---

## 📁 Dataset
- **Source:** Kaggle — Sample Sales Data by Gus Segura
- **Records:** 2,823 transactions
- **Columns used:** SALES, ORDERDATE, PRODUCTLINE, COUNTRY, DEALSIZE, QUANTITYORDERED

---

## 🔍 Steps Performed
1. Loaded CSV data using Pandas
2. Checked data types and shape
3. Identified and removed missing value columns (ADDRESSLINE2, STATE, TERRITORY)
4. Converted ORDERDATE from string to datetime format
5. Extracted MONTH and YEAR columns for trend analysis
6. Performed groupby analysis on Country, Product Line, Deal Size
7. Created 4 visualizations using Matplotlib
8. Built a static website using HTML & CSS

---

## 📈 Key Findings
- **USA** is the top revenue country with **$3.6M** in sales
- **Classic Cars** is the best-selling product line with **$3.9M** revenue
- **Medium deal size** contributes the most — **60%** of total revenue
- Total revenue across all years: **$10.03M**

---

## 📂 Project Structure
sales-analysis/

├── index.html

├── style.css

├── chart_countries.png

├── chart_products.png

├── chart_dealsize.png

└── chart_monthly.png

---

## 🌐 Live Website
[View Project Website](https://Smith11022006.github.io/sales-analysis/)

---

## 👤 Author
**Smith Pratik Lenka** | Final Year BCA Student | Sardar Vallabhbhai Global University, Ahmedabad
