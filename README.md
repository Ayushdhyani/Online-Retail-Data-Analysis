# Online Retail Sales Data Analysis

## Data Science Internship – Week 1 Assignment

**Organization:** WeIntern Pvt. Ltd.  
**Intern:** Ayush Dhyani  
**College:** THDC Institute of Hydropower Engineering and Technology (THDC-IHET)  
**Project:** Online Retail Sales Data Analysis

---

## 1. Project Overview

This project focuses on cleaning, analyzing, and visualizing an Online Retail dataset using Python.

The main objective is to understand sales performance, identify top-selling products, analyze customer purchasing behavior, and discover important business trends.

This project was completed as part of the Week 1 Data Science Internship assignment at WeIntern Pvt. Ltd.

## 2. Dataset Source

The dataset used in this project is the **Online Retail Dataset** from the UCI Machine Learning Repository.

- Source: UCI Machine Learning Repository
- Dataset: Online Retail
- Period: December 2010 – December 2011
- Original Records: 541,909

Dataset link: https://archive.ics.uci.edu/dataset/352/online+retail

## Dataset

The cleaned dataset is approximately 102 MB
and is not included in this repository due
to GitHub's file upload size limitations.

The dataset is stored locally.

## 3. Tools and Technologies

The following tools and libraries were used:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL

## 4. Project Workflow

The project was completed through the following steps:

1. Dataset loading and initial inspection.
2. Identification and treatment of missing values.
3. Duplicate record detection and removal.
4. Data validation and preprocessing.
5. Creation of additional columns for transaction classification.
6. Calculation of sales KPIs.
7. Customer and product analysis.
8. Monthly and country-wise sales analysis.
9. Creation of charts and a sales dashboard.
10. Documentation of findings and conclusions.

## 5. Data Cleaning Summary

- Original records: 541,909
- Duplicate records removed: 5,268
- Remaining missing product descriptions removed: 112
- Final cleaned records: 536,529
- Final columns: 10

Negative quantities were retained because they may represent returns or cancellations. Zero and negative prices were identified and excluded from regular revenue calculations.

The cleaned dataset was saved separately to preserve the original raw data.

## 6. Key Performance Indicators

| KPI | Result |
|---|---:|
| Gross Sales Revenue | £10,640,211.08 |
| Net Sales Revenue | £9,748,131.07 |
| Total Orders | 19,960 |
| Total Units Sold | 5,572,420 |
| Average Order Value | £ 533.17 |

## 7. Key Findings

- The United Kingdom generated the highest sales revenue.
- November recorded the highest monthly sales revenue.
- PAPER CRAFT, LITTLE BIRDIE was the top-selling product by quantity, with 80,995 units sold.
- DOTCOM POSTAGE generated the highest product-level revenue.
- Total identified customers: 4,338.
- Repeat customers: 2,845.
- Repeat customer percentage: 65.58%.
- Repeat customers contributed 93.09% of revenue from customers with available CustomerID values.

## 8. Visualizations

The project includes visualizations to understand:

- Top countries by sales revenue.
- Top products by units sold.
- Monthly sales trends.
- Key sales KPIs and customer insights through a dashboard mockup.

All generated charts are stored in the `outputs/charts/` directory.

## 9. Limitations

- Some CustomerID values are missing, limiting customer-level analysis.
- The dataset does not contain a product Category column, so category-wise analysis could not be performed.
- Negative quantities may represent returns or cancellations.
- The dataset covers a limited historical period.
- The analysis identifies sales patterns but does not establish the causes behind them.

## 10. Project Folder Structure

```text
data-science-week1-assignment/
│
├── data/
│   ├── raw/
│   │   └── Online_Retail.xlsx
│
├── notebooks/
│   └── week1_analysis.ipynb
│
├── outputs/
│   └── charts/
│
├── README.md
└── requirements.txt
```

## 11. How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `notebooks/week1_analysis.ipynb`.
5. Run the notebook cells in sequential order.

## 12. Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, KPI calculation, customer analysis, and data visualization using Python.

It helped develop an understanding of how raw transactional data can be transformed into meaningful business insights.

The project also improved practical knowledge of Pandas, NumPy, Matplotlib, and data analysis workflows.

---

**Submitted by:** Ayush Dhyani  
**College:** THDC-IHET  
**Internship:** Data Science Internship – Week 1  
**Organization:** WeIntern Pvt. Ltd.
