# 🚗 VOIS Internship – Car Market Analysis | Car Dekho Data

> An end-to-end Data Analytics and Exploratory Data Analysis project developed as part of the **VOIS Internship**, using Car Dekho used-car market data with Python.

---

## 📌 Project Overview

This project focuses on analyzing used-car market data from Car Dekho using Python and Exploratory Data Analysis (EDA) techniques.

The objective is to understand the factors associated with used-car selling prices and identify important market trends across:

- Vehicle price
- Manufacturing year
- Car age
- Fuel type
- Transmission
- Seller type
- Previous owners
- Kilometers driven
- Car model
- Price retention
- Depreciation

The project follows a complete data analytics workflow from **data loading and cleaning to visualization, correlation analysis, business insights, and recommendations**.

---

## 🎯 Problem Statement

The used-car market contains vehicles with different prices, models, manufacturing years, fuel types, transmission types, seller types, ownership histories, and usage levels.

It can be difficult for buyers, sellers, and dealers to understand which factors are associated with a vehicle's selling price.

This project uses historical Car Dekho data to analyze pricing patterns and generate data-driven insights that can support used-car market decisions.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Load and understand the Car Dekho dataset
- Perform data quality checks
- Identify and remove duplicate records
- Check for missing values
- Analyze numerical variables
- Analyze categorical variables
- Analyze selling-price distribution
- Study manufacturing year and selling price
- Compare selling prices by fuel type
- Compare selling prices by transmission
- Compare selling prices by seller type
- Analyze kilometers driven and selling price
- Analyze ownership history
- Analyze car age and price retention
- Calculate depreciation
- Perform correlation analysis
- Generate meaningful business insights
- Provide business recommendations
- Present the findings using charts and PowerPoint

---
### 🔑 Key Business Insights

- 📊 The cleaned dataset contains **299 records** and **98 unique car names**.
- ✅ The supplied dataset contains **0 missing values**.
- 🔄 **2 exact duplicate rows** were identified before data cleaning.
- 💰 The **average selling price is 4.59**, while the **median selling price is 3.51**.
- 🛣️ The **average kilometers driven is approximately 36,917**, with a **median of 32,000 km**.
- 📈 Selling Price has a **strong positive correlation of 0.876** with Present Price.
- 📅 Selling Price has a **0.234 correlation** with Manufacturing Year, indicating a positive but relatively weak relationship.
- 🛣️ Selling Price has only a **0.029 correlation** with Kilometers Driven, indicating a **very weak linear relationship**.
- ⛽ **Diesel** is the fuel category with the **highest average selling price** in this dataset.
- ⚙️ **Automatic** is the transmission category with the **higher average selling price**.
- 🏪 **Dealer** is the seller category with the **higher average selling price**.

### 📌 Business Interpretation

> The analysis suggests that **Present Price is the strongest numerical indicator associated with Selling Price**, while Kilometers Driven has a very weak linear relationship with selling price. Vehicle category characteristics such as **fuel type, transmission, and seller type** also show noticeable differences in average selling prices.

> **Note:** Correlation indicates association and does not prove causation. Category-level price differences may also be influenced by vehicle model, age, and the composition of the dataset.
---

# 📊 Dataset

The dataset used for this project is:

**`Car Market Trends Analysis with Car Dekho Data.csv`**

## Dataset Features

| Column | Description |
|---|---|
| `Car_Name` | Name/model of the vehicle |
| `Year` | Manufacturing year |
| `Selling_Price` | Selling price of the used vehicle |
| `Present_Price` | Present/reference price of the vehicle |
| `Kms_Driven` | Total kilometers driven |
| `Fuel_Type` | Fuel type of the vehicle |
| `Seller_Type` | Type of seller |
| `Transmission` | Transmission type |
| `Owner` | Number of previous owners |

---

# 📈 Dataset Summary

| Metric | Value |
|---|---:|
| Original Records | 301 |
| Duplicate Records Removed | 2 |
| Final Records | 299 |
| Unique Car Names | 98 |
| Missing Values | 0 |
| Average Selling Price | 4.59 |
| Median Selling Price | 3.51 |
| Average Present Price | 7.54 |
| Average Kms Driven | 36,917 km |
| Median Kms Driven | 32,000 km |
| Average Car Age | 5.38 years |
| Average Price Retention | 63.38% |
| Average Depreciation | 36.62% |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
