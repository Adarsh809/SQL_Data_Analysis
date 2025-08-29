# SQL Data Analysis  

## 📌 Overview  
This project demonstrates how to perform **SQL-based data analysis** on an **E-commerce dataset** using **MySQL** and **Python**.  

The workflow involves:  
- Importing CSV files into MySQL  
- Running SQL queries to extract insights  
- Using **Pandas**, **Matplotlib**, and **Seaborn** for data visualization  

It serves as a practical guide for anyone learning **SQL for analytics** combined with **Python for visualization**.  

---

## ⚙️ Setup Instructions  

### 1. Clone the Repository  
```bash
git clone https://github.com/Adarsh809/SQL_Data_Analysis.git
cd SQL_Data_Analysis
```

### 2. Install Dependencies  
```bash
pip install pandas mysql-connector-python matplotlib seaborn
```

### 3. Setup MySQL Database  
1. Install and start MySQL server.  
2. Create a database named `ecommerce`.  
   ```sql
   CREATE DATABASE ecommerce;
   ```
3. Update your MySQL credentials inside the notebook (`SQL_Data_Analysis.ipynb`).  
4. Place the CSV dataset inside the `archive/` folder.  

---

## 📂 Dataset  
The dataset consists of multiple CSV files related to e-commerce transactions:  
- **customers.csv** → Customer details  
- **orders.csv** → Order information with timestamps  
- **sellers.csv** → Seller details  
- **products.csv** → Product catalog  
- **geolocation.csv** → Customer locations  
- **payments.csv** → Payment details  
- **order_items.csv** → Items purchased per order  

---

## 🔎 Analysis Performed  

Some of the key SQL queries executed in the project:  
- List of all **unique customer cities**  
- **Count of orders** placed in 2017  
- **Total sales per product category**  
- **Percentage of installment payments**  
- **Customer distribution by states**  
- **Orders per month in 2018** (visualized using bar chart)  
- **Average number of products per order** grouped by customer city  
- **Revenue contribution by product category**  

---

## 📊 Visualizations  
The notebook generates several visual insights, such as:  
- **Customer count by states** (bar chart)  
- **Monthly order trends in 2018** (bar chart with labels)  
- **Sales distribution by category**  

Example Visualization:  

![Customer Count by State](assets/customer_count.png)  
![Orders in 2018](assets/orders_2018.png)  

---

## 🚀 Usage  
- Run the notebook step by step to:  
  1. Create tables in MySQL  
  2. Load CSV data into the database  
  3. Execute SQL queries for analysis  
  4. Visualize insights with **Matplotlib/Seaborn**  

- Modify SQL queries to explore additional insights.  
- Extend visualizations for deeper analysis.  

---

## 📌 Tech Stack  
- **SQL (MySQL)** – Data storage & querying  
- **Python** – Data processing & automation  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  

---

## 📜 License  
This project is for educational purposes.  
Feel free to fork, modify, and use it for learning or personal projects 🚀.  
