# Blinkit Sales Performance Analysis using Pandas 🛒

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Latest-ff69b4?logo=pandas)

An end-to-end data analysis project focusing on retail operations and sales performance. This project leverages Python's **Pandas** library for data cleaning, KPI calculation, and uncovering structural insights from Blinkit's retail data.

---

## 📌 Project Overview
The objective of this analysis is to identify key sales trends and efficiency metrics across various outlet types and locations using programmatic data manipulation. By processing over **8,500 records**, this project provides a clear picture of how item attributes and store characteristics influence total revenue.

---

## 📊 Key Insights (KPIs)
| Total Sales | Avg Sales | Items Sold | Avg Rating |
| :---: | :---: | :---: | :---: |
| **$1.20M** | **$141.00** | **8,523** | **4.0 ⭐** |

---

## 📖 Data Summary
The dataset contains **8,523 records** with 12 distinct features:

| Column Name | Description |
| :--- | :--- |
| **Item Identifier** | Unique ID assigned to each product. |
| **Item Fat Content** | Categorizes product as 'Low Fat' or 'Regular'. |
| **Item Type** | Broad category (e.g., Dairy, Snack Foods). |
| **Item Weight** | Physical weight of the product. |
| **Item Visibility** | % of total display area allocated in store. |
| **Outlet Identifier** | Unique ID for each retail store. |
| **Outlet Establishment Year** | The year the store was founded. |
| **Outlet Size** | Store ground area (Small, Medium, High). |
| **Outlet Location Type** | City tier classification (Tier 1, 2, or 3). |
| **Outlet Type** | Store model (e.g., Grocery Store, Supermarket). |
| **Sales** | Total revenue generated (Target Variable). |
| **Rating** | Average customer satisfaction score. |

---

## 🛠 Analysis Workflow
The analysis was performed through a structured three-step process:

1.  **Data Cleaning 🧼**
    * Standardized `Item Fat Content` labels (merged 'LF', 'low fat', and 'reg' into 'Low Fat' and 'Regular').
    * Handled missing values and verified data types.
2.  **KPI Calculation 📈**
    * Aggregated metrics using `.sum()`, `.mean()`, and `.count()`.
3.  **Market Segmentation 🎯**
    * Used `.groupby()` to analyze performance across city tiers, outlet sizes, and item categories.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`
* **Tools:** Jupyter Notebook

---
