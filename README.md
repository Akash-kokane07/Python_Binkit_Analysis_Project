# **Blinkit Sales Analysis – Python Data Analytics Project**

## **Project Overview**

This project performs an end-to-end Exploratory Data Analysis (EDA) on Blinkit’s sales dataset using Python. The goal is to uncover insights about product performance, outlet characteristics, sales trends, and customer preferences.

The project demonstrates:

* Data cleaning and preprocessing
* Descriptive statistics
* Visual EDA using Matplotlib & Seaborn
* KPI calculations
* Actionable business insights


## **Tech Stack**

* **Python**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code


## **Key KPIs**

| Metric                     | Value     |
| -------------------------- | --------- |
| **Total Sales**            | 1,201,681 |
| **Average Sales per Item** | 141       |
| **Items Sold**             | 8,523     |
| **Average Rating**         | 4.0       |


## **Key Insights**

### **1. Fat Content**

* **Low Fat** items generate **64.6%** of total sales.
* Health-oriented products show higher demand.

### **2. Item Type**

Top-selling categories:

* **Fruits & Vegetables**
* **Snack Foods**
* **Household Items**

Low-selling categories:

* **Seafood**
* **Breakfast**

### **3. Outlet Location Performance**

* **Tier 3 outlets generate the highest revenue**.
* Followed by Tier 2 and Tier 1.

### **4. Outlet Size**

* Medium outlets perform best.
* High-size outlets underperform.

### **5. Outlet Establishment Year**

* Older outlets (1998–2000) show stronger and more stable sales.


## **Visualizations Included**

* Sales by Fat Content (Pie Chart)
* Sales by Item Type (Bar Graph)
* Outlet Tier vs Fat Content
* Sales by Establishment Year (Line Chart)
* Sales by Outlet Size (Pie Chart)
* Sales by Outlet Location Type (Bar Chart)

## **Data Cleaning Steps**

* Standardized “Item Fat Content”
* Handled inconsistent labels
* Checked data types & missing values
* Formatted categorical columns

## 🧾 **Conclusion**

The analysis provides crucial insights into customer behavior, product demand, and outlet performance. It helps Blinkit optimize inventory, improve marketing strategy, and strengthen outlet planning.


## 🚀 **How to Run the Project**

1. Clone the repository
2. Install dependencies
3. Run the Jupyter Notebook or Python script

```bash
pip install -r requirements.txt
```

```python
python blinkit_analysis.py
```
