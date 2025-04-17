# 🛍️ Task 7 –  Basic Sales Summary from a Tiny SQLite Database using Python

This project is part of a **Data Analyst Internship Task** where the objective is to build a basic sales summary using **SQL inside Python**, and visualize the results using **Matplotlib**.

---

## 📘 Problem Statement

Create a SQLite database and extract sales insights using SQL queries within Python. Display the output both via `print` statements and a **simple bar chart**. This is a fundamental task for understanding how SQL and Python work together for data analysis.

---

## 🧰 Tools Used

- **Python 3**
- **SQLite3** – built-in Python SQL engine
- **Pandas** – for handling dataframes
- **Matplotlib** – for plotting charts
- **Google Colab** – for executing everything in the cloud

---

## 💾 Dataset Details

The sales data simulates transactions from a fictional store with the following schema:

| Column   | Type     | Description                |
|----------|----------|----------------------------|
| id       | INTEGER  | Unique sale ID             |
| product  | TEXT     | Name of the product sold   |
| quantity | INTEGER  | Quantity sold              |
| price    | INTEGER  | Price per unit (in ₹ INR)  |

The dataset is manually created and inserted into a SQLite table named `sales`. Each row represents a product sale with:
- `product` (name)
- `quantity` (units sold)
- `price` (per unit)

--

### 🧪 Sample Data used for task

| Product     | Quantity | Price |
|-------------|----------|-------|
| Smartwatch  | 2        | 5000  |
| Headphones  | 3        | 3000  |
| Hoodie      | 5        | 1200  |
| Sneakers    | 4        | 2500  |
| Smartwatch  | 1        | 5000  |
| Hoodie      | 2        | 1200  |

--

## 📊 Chart Highlights:

*📱 Smartwatch generated the highest revenue
*👕 Hoodie had the highest quantity sold, but lower unit price
*🎧 Headphones and 👟 Sneakers showed good performance

--

## 📁 Project structure
├── 📜 sales_data.db                    # SQLite database file
├── 📜 task7_python_script.ipynb        # Colab notebook with SQL + analysis
├── 📊  sales_chart.png                 # Revenue chart generated by matplotlib
├── 📄 README.md                        # Project documentation

--

## 📌 Skills Demonstrated
-Creating and modifying SQLite tables with Python
-Writing and executing SQL queries using sqlite3
-Loading SQL results into Pandas DataFrames
-Visualizing business insights using Matplotlib
-Clear storytelling through charts and tables

--

##  ✨ Summary

This project demonstrates how to integrate SQL with Python to perform basic data analysis on a sales dataset stored in a SQLite database. Using a fictional dataset, I queried total quantities and revenues by product, then visualized the revenue data with a clear and informative bar chart.

The key takeaways from this task include:
- Creating and querying a SQLite database using Python
- Writing SQL queries to aggregate data
- Loading SQL results into Pandas for further analysis
- Plotting insights using Matplotlib and Seaborn
- Presenting business insights clearly and visually

This project showcases my ability to blend SQL, Python, and data visualization — core skills required for any entry-level data analyst role.


## 👋 About Me
I'm a passionate aspiring Data Analyst, constantly exploring ways to convert raw data into meaningful insights using Python, SQL, and powerful visualizations.

## 📞 Let's connect

- 📧 Email ID : sirishadsirishad6@gmail.com
- 💼 LinkedIn : https://www.linkedin.com/in/sirisha-d-064b69278/






