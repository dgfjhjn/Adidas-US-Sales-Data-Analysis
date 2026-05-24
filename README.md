# Adidas US Sales Data Analysis

![Adidas Banner](adidas.jpg)

## 📌 Project Overview
This project delivers a comprehensive **Data Analysis and Interactive Visualization** of Adidas sales performance across the United States. Utilizing Python, Pandas, and Plotly, the analysis uncovers key business insights regarding regional performance, product profitability, sales methods, and temporal trends to optimize business strategies.

## 🚀 Key Features
* **Data Cleaning & Preprocessing:** Handling multi-row headers, formatting currency values, and structuring datetime fields for analysis.
* **Geographical Insights:** Mapping and visualizing total sales and operating profits across different US regions, states, and cities.
* **Product Performance Evaluation:** Identifying top-performing product categories (e.g., Footwear vs. Apparel) based on revenue and operating margins.
* **Sales Channel Analysis:** Comparing the efficiency and profitability of different sales methods (`In-store`, `Outlet`, and `Online`).
* **Interactive Dashboards:** Leveraging dynamic Plotly charts for deep-dive exploratory data analysis (EDA).

## 🛠️ Technologies Used
* **Language:** Python 3.x
* **Libraries:** * `pandas` (Data manipulation and aggregation)
  * `plotly.express` / `plotly.graph_objects` (Interactive data visualization)
  * `matplotlib` & `seaborn` (Static plotting & styling)

## 📖 Quick Start: Reading the Data
To load and view the clean structure of the dataset, you can use the following snippet:

```python
import pandas as pd

# Load the Adidas US Sales Dataset (Skipping the header rows from the raw file)
df = pd.read_csv('Adidas US Sales Datasets.xlsx - Data Sales Adidas.csv', skiprows=4)

# Clean column names (remove leading/trailing spaces)
df.columns = df.columns.str.strip()

# View the first few rows
print(df.head())




