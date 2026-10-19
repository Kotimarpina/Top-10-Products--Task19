# Task 17: Top 10 Products by Sales

## 📌 Project Overview

This project identifies the **Top 10 products by total sales** using the Sample Superstore dataset. It demonstrates how Python can be used to aggregate sales data, sort products, rank results, and visualize business insights.

This task was completed as part of my Data Analytics Internship at **Veda Technologies**.

## 🎯 Objectives

- Identify the 10 products with the highest total sales.
- Aggregate sales across multiple order records for each product.
- Sort and rank products based on total sales.
- Visualize the top-performing products using a horizontal bar chart.
- Understand how ties are handled when products have equal sales values.

## 🛠️ Tools and Technologies

- **Python** — Data analysis
- **pandas** — Data manipulation and aggregation
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive coding and analysis

## 📂 Dataset

**Dataset:** Sample Superstore

The analysis uses the following columns:

- `Product Name` — Name of the product.
- `Sales` — Sales value associated with each order record.

## 🔍 Methodology

1. Imported the required Python libraries.
2. Loaded the Orders worksheet from the Sample Superstore Excel workbook.
3. Inspected the dataset and checked the relevant columns.
4. Grouped records by product name and calculated total sales.
5. Sorted products in descending order of total sales.
6. Selected and ranked the top 10 products.
7. Created a horizontal bar chart to compare their sales.
8. Exported the results to a CSV file.

## 📊 Key Analysis

The analysis produces:

- A ranked table of the top 10 products by total sales.
- A horizontal bar chart comparing sales performance.
- The highest-selling product and its total sales.
- A ranked list that uses product name as a consistent tie-breaker when sales values are equal.

**Note:** The analysis ranks products by total sales, not profit. High sales do not necessarily mean high profitability.

## 📁 Repository Structure

```text
Task-17-Top-10-Products-by-Sales/
├── README.md
├── Task_17_Top_10_Products_by_Sales.ipynb
├── Sample - Superstore Sales (Excel).xls
└── top_10_products_by_sales.csv
```

The dataset and generated CSV should be included only if permitted by the dataset's usage terms. The CSV is generated when the notebook runs successfully.

## ▶️ How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib openpyxl xlrd
   ```

3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Ensure the Excel file path and worksheet name are correct.
5. Run the notebook cells in order.

## 💡 Key Learning Outcomes

- Aggregating repeated records using `groupby()`.
- Calculating total sales for each product.
- Sorting data and selecting the top 10 records.
- Visualizing rankings with Matplotlib.
- Understanding tie-handling approaches in ranking tasks.

## ✅ Conclusion

This project demonstrates a simple and effective approach to identifying top-selling products using Python. The resulting summary table and chart make it easier to compare product sales and support further business analysis.

---

**Internship:** Data Analytics Internship  
**Organization:** Veda Technologies  
**Task:** Task 17 — Top 10 Products by Sales
