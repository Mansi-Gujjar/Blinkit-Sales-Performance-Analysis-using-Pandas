# Blinkit Sales Performance Analysis using Pandas 🛒

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-ff69b4?style=for-the-badge&logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end data analysis project focusing on retail operations and sales performance. This project leverages Python's **Pandas** library for rigorous data cleaning, KPI calculation, and uncovering structural insights from Blinkit's retail dataset.

---

## 📌 Project Overview
The objective of this analysis is to identify key sales trends and efficiency metrics across various outlet types and locations. By processing over **8,500 records**, this project provides a clear picture of how item attributes (like fat content and visibility) and store characteristics (like size and location) influence total revenue.

---

## 📊 Key Insights (KPIs)
> **Summary of findings derived from `blinkit.ipynb`**

| Total Sales | Avg Sales | Items Sold | Avg Rating |
| :---: | :---: | :---: | :---: |
| **$1.20M** | **$141.00** | **8,523** | **4.0 ⭐** |

---

## 📖 Data Dictionary
The analysis is based on **8,523 records** with 12 distinct features:

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
The analysis follows a professional data science lifecycle using Pandas:

### 1. Data Cleaning 🧼
* **Standardization:** Unified `Item Fat Content` labels (merged 'LF', 'low fat', and 'reg' into 'Low Fat' and 'Regular').
* **Validation:** Handled missing values in `Item Weight` and checked for data type consistency.

### 2. KPI Calculation 📈
* **Aggregation:** Leveraged `.sum()`, `.mean()`, and `.count()` to derive global business metrics.

### 3. Market Segmentation 🎯
* **Drill-down:** Utilized `.groupby()` and pivot-style logic to compare performance across city tiers, outlet sizes, and item categories.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Primary Library:** `Pandas`
* **Supporting Library:** `NumPy`
* **Environment:** Jupyter Notebook

---

## 🚀 How to Use
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/blinkit-sales-pandas-analysis.git](https://github.com/your-username/blinkit-sales-pandas-analysis.git)
