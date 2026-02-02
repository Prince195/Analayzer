# Analayzer

# 📊 Sales Data Analyzer & Visualization Tool (Python)

## 📌 Project Overview

The **Sales Data Analyzer** is a **menu-driven, object-oriented Python application** designed to perform **data analysis, cleaning, aggregation, and visualization** on sales datasets stored in CSV format.

This project demonstrates **core Python concepts**, **data analysis theory**, and **real-world usage of popular libraries** such as **Pandas, NumPy, Matplotlib, and Seaborn**.
It is especially useful for **students, beginners in data science, and academic projects**.

---
## 🎯 Objectives of the Project

* To understand **how real-world sales data is processed**
* To apply **Object-Oriented Programming (OOP)** in Python
* To perform **exploratory data analysis (EDA)**
* To handle **missing or inconsistent data**
* To visualize business insights using **graphs and charts**
* To build a **console-based interactive program**
---
## 🧠 Theoretical Concepts Covered

### 1️⃣ Object-Oriented Programming (OOP)

This project follows an **OOP-based design** using a class:

* **Class:** `SalesDataAnalyzer`
* **Constructor (`__init__`)** initializes the dataset
* **Methods** perform specific operations like loading, cleaning, visualizing data
* **Destructor (`__del__`)** handles cleanup

✔ Benefits of OOP in this project:

* Better code organization
* Reusability of methods
* Easier maintenance
* Real-world programming structure

--
### 2️⃣ Data Handling with Pandas

Pandas is used for **reading, exploring, and manipulating tabular data**.

Key operations include:

* Loading CSV files using `read_csv()`
* Viewing dataset structure (`head()`, `tail()`)
* Checking column names and data types
* Generating summary statistics using `describe()`

📌 Pandas allows efficient handling of **large datasets**.

---

### 3️⃣ Numerical Computation with NumPy

NumPy is used for **mathematical and numerical operations**.

Examples:

* Converting sales data into NumPy arrays
* Performing element-wise operations (e.g., tax calculation)
* Fast numerical computation

📌 NumPy improves performance compared to plain Python lists.

---

### 4️⃣ Data Cleaning & Missing Value Handling

Real datasets often contain **missing or null values**.

This project supports:

* Identifying rows with missing values
* Filling missing numeric values using **mean**
* Removing incomplete rows

✔ Importance:

* Prevents incorrect analysis
* Improves data quality
* Ensures accurate visualizations

---

### 5️⃣ Sorting, Searching & Aggregation

* Sorting sales data in **descending order**
* Finding top sales values
* Generating **descriptive statistics**

  * Mean
  * Median
  * Standard deviation
  * Min / Max values

📊 These operations help in **business decision-making**.

---

### 6️⃣ Data Visualization (Theory + Practice)

Visualization is crucial to **understand patterns and trends**.

The project supports:

* **Bar Charts** → Sales comparison by region
* **Line Charts** → Sales trends over time
* **Scatter Plots** → Relationship between variables
* **Pie Charts** → Category-wise distribution
* **Histograms** → Frequency distribution

Libraries used:

* **Matplotlib** → Base plotting
* **Seaborn** → Advanced statistical visuals

📌 Visualizations make data **easy to interpret and present**.

---

### 7️⃣ Menu-Driven Console Application

The application uses a **loop-based menu system** that allows users to:

* Choose operations interactively
* Perform tasks step-by-step
* Avoid writing code repeatedly

✔ This improves **usability and user experience**.

---

## 🛠️ Technologies & Libraries Used

| Tool / Library | Purpose                   |
| -------------- | ------------------------- |
| Python         | Core programming language |
| Pandas         | Data handling & analysis  |
| NumPy          | Numerical computation     |
| Matplotlib     | Plotting graphs           |
| Seaborn        | Statistical visualization |

---

## 📂 Project Structure

```
Sales-Data-Analyzer/
│
├── visualizer.py        # Main Python program
├── sales_data.csv       # Sample dataset
├── README.md            # Project documentation
```

---

## ▶️ How to Run the Project

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Run the program:

```bash
python visualizer.py
```

3. Follow the on-screen menu options.
