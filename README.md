# CodeTech-02
# 📊 Automated Sales Report Generator

This project is a Python-based solution to generate a comprehensive PDF report from a sales dataset (`sales_100k_clean.csv`). It was developed as part of an internship task focused on automation, data analysis, and report formatting.

---

## 🔧 Features

- Reads sales data from a CSV file using **pandas**
- Performs descriptive analysis (mean, min, max, etc.)
- Generates visual charts using **matplotlib**:
  - Bar chart of top sales regions
  - Pie chart of product categories
  - Bar chart of customer gender distribution
- Creates a styled multi-page PDF report using **fpdf2**
- Includes:
  - Title page
  - Table of contents
  - Summary statistics
  - Top 5 sales records
  - Charts
  - Page numbers

---

## 📂 Files Included

├── sales_100k_clean.csv # Input dataset
├── generate_report.py # Main Python script
├── sales_report_final.pdf # Output PDF report
├── region_chart.png # Chart: Sales by region
├── product_pie.png # Chart: Product categories
├── gender_chart.png # Chart: Gender distribution
└── README.md # Project documentation

##📌 Technologies Used
Python 3.x
pandas – for data analysis
matplotlib – for charts and visualizations
fpdf2 – for generating PDF reports

