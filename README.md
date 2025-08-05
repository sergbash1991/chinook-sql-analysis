# 💼 Revenue Analysis by Country — Chinook DB

This project analyzes which countries generate the **highest revenue per customer** and how they compare in terms of **total revenue** using the Chinook SQLite database.

![Main Visualization](./Screenshot_5.jpg) <!-- Update with your actual image path -->

---

## 📌 Objective

To answer the question:  
**"Which countries generate the most revenue per customer, and how do they compare to others?"**

---

## 🔍 Analysis Workflow

1. **Import Libraries**  
   NumPy, Pandas, Matplotlib, SQLite3.

2. **Connect to SQLite Database**  
   Explore available tables using `sqlite_master`.

3. **Database Exploration in DBeaver**  
   Used ER diagram to understand table relationships and plan SQL joins.

4. **Data Extraction with SQL**  
   - Join `Customer` and `Invoice` tables  
   - Calculate total revenue and average revenue per customer by country  
   - Load data into Pandas DataFrame

5. **Visualization**  
   - Pie chart: Total Revenue by Country (Top 8)  
   - Bar chart: Average Revenue per Customer by Country (Top 8)

---

## 📊 Insights

- Countries like **Chile, Ireland, and Hungary** show the highest **revenue per customer**
- The **USA** leads in total revenue due to a larger number of customers

---

## 🛠 Skills & Tools Used

- Python: `pandas`, `matplotlib`, `sqlite3`
- SQL: `JOIN`, `GROUP BY`, `SUM`, `COUNT`, `ORDER BY`
- Data exploration with **DBeaver**
- Data visualization & storytelling

---

## 🚀 Author

**Bashkatov Sergii**  
Open to Data Analyst opportunities  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sergii-bashkatov-a792a8113)
