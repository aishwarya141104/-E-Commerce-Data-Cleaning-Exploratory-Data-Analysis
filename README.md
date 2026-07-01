# 🛒 E-Commerce Data Cleaning & Exploratory Data Analysis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github)

</p>

---

## 📌 Project Overview

This project demonstrates a complete **Data Cleaning and Exploratory Data Analysis (EDA)** workflow on an E-Commerce sales dataset containing **1200 customer orders**.

The objective is to clean the raw dataset, identify missing values, perform feature engineering, analyze business performance, and visualize key insights using Python.

---

# 📊 Dataset Information

| Attribute | Value |
|------------|--------|
| Dataset Type | E-Commerce Sales |
| Total Records | 1200 |
| Total Columns | 14 |
| Missing Values | CouponCode (309) |
| Duplicate Rows | 0 |
| Data Source | Excel (.xlsx) |

---

# 🗂 Dataset Features

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

---

# 🎯 Objectives

- Perform data cleaning
- Handle missing values
- Detect duplicates
- Perform feature engineering
- Generate business insights
- Create professional visualizations
- Export cleaned dataset

---

# ⚙ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Cleaning |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Jupyter Notebook | Development Environment |

---

# 📁 Project Structure

```
Data_Cleaning_Project
│
├── Dataset for Data Analytics.xlsx
├── cleaned_dataset.csv
├── Data_Cleaning_Project.ipynb
├── README.md
│
├── images
│   ├── dataset.png
│   ├── missing_values.png
│   ├── product_sales.png
│   ├── payment_method.png
│   ├── revenue_product.png
│   ├── monthly_sales.png
│   ├── correlation.png
│   └── ...
│
└── report.pdf
```

---

# 🧹 Data Cleaning Process

✔ Imported dataset

✔ Checked data types

✔ Checked missing values

✔ Filled missing CouponCode with **"No Coupon"**

✔ Verified duplicates

✔ Outlier detection

✔ Created new Date features

✔ Exported cleaned dataset

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

- Product-wise Sales
- Revenue by Product
- Monthly Sales Trend
- Payment Method Analysis
- Coupon Usage Analysis
- Referral Source Analysis
- Order Status Distribution
- Quantity Distribution
- Unit Price Distribution
- Top Customers
- Items in Cart Analysis
- Daily Orders
- Correlation Heatmap
- Yearly Revenue
- Boxplot Analysis

---

# 📷 Project Screenshots

## Dataset Preview

![Dataset](images/dataset.png)

---

## Missing Values

![Missing Values](images/missing_values.png)

---

## Product Sales

![Product Sales](images/product_sales.png)

---

## Monthly Sales Trend

![Monthly Sales](images/monthly_sales.png)

---

## Revenue by Product

![Revenue](images/revenue_product.png)

---

## Correlation Matrix

![Correlation](images/correlation.png)

---

# 📊 Business Insights

### ✔ Dataset Quality

- Dataset contains **1200 records**
- No duplicate entries
- Only one column contains missing values

---

### ✔ Customer Behaviour

- Customers prefer selected payment methods over others.
- Coupon usage is relatively low compared to non-coupon purchases.

---

### ✔ Product Performance

- Some products generate significantly higher revenue.
- High-priced products contribute most to total sales.

---

### ✔ Sales Trend

- Monthly revenue shows seasonal fluctuations.
- Business experiences peak sales during specific months.

---

### ✔ Marketing

- Referral sources contribute differently to sales.
- Social media channels generate valuable customer traffic.

---

# 📌 Future Improvements

- Dashboard using Power BI
- Tableau Dashboard
- Machine Learning Sales Prediction
- Customer Segmentation
- Sales Forecasting
- Interactive Streamlit Dashboard

---

# ▶ How to Run

Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
```

Go to project folder

```bash
cd YOUR_REPOSITORY_NAME
```

Install dependencies

```bash
pip install pandas numpy matplotlib openpyxl
```

Run Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Data_Cleaning_Project.ipynb
```

---

# 📦 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

---

# 📜 License

This project is developed for educational and portfolio purposes.

---

# 👩‍💻 Author

**Aishwarya Kulkarni**

GitHub:
https://github.com/aishwarya141104

---

## ⭐ If you found this project useful,

Please consider giving it a ⭐ on GitHub!
