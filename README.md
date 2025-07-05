# 🧾 Task 7: Basic Sales Summary using SQLite and Python

## 🎯 Objective  
Use SQL inside Python to pull simple sales data (like total quantity sold and total revenue) from a SQLite database, and display results using print statements and a basic bar chart.

---

## 📚 Description  
This notebook connects to a small SQLite database (`sales_data.db`) and creates a `sales` table with sample data. Using SQL queries, it calculates:

- Total quantity sold per product  
- Total revenue (quantity × price) per product  

The results are printed using `pandas` and visualized using `matplotlib`.

---

## 🛠 Tools Used  
- Python  
- SQLite3  
- Pandas  
- Matplotlib  
- Google Colab (for running the notebook)

---

## 📁 Dataset Info  
The dataset is generated inside the notebook using Python code.  
The `sales` table includes:
- `product` (e.g., Pen, Notebook, Marker)  
- `quantity`  
- `price`

---

## 🧪 What the Notebook Does  
1. Creates the `sales_data.db` database and `sales` table  
2. Inserts sample data  
3. Runs an SQL query to summarize product sales  
4. Loads the results into a DataFrame and prints it  
5. Plots a bar chart showing revenue by product

---

## 📌 How to View Output  
⚠️ **Note:** This repo only contains the `.ipynb` file.  
To see the output:
- Open the notebook in **Google Colab**
- Run all the cells to generate the output table and chart

---

## ✅ What I Learned  
- Writing basic SQL queries using Python  
- Connecting SQLite with Pandas  
- Summarizing and visualizing data with matplotlib
