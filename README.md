# 🛒 ShopSphere Analytics

## E-Commerce Sales & Customer Analytics

ShopSphere Analytics is a data analytics project designed to analyse e-commerce sales, customer behaviour, products, payments, reviews, and revenue trends using **MySQL and Python**.

---

## 🎯 Project Objective

The main objective of this project is to extract meaningful insights from an e-commerce database using SQL queries and Python-based data analysis.

The project focuses on:

* Customer analysis
* Order analysis
* Product performance
* Revenue analysis
* Payment analysis
* City-wise sales analysis
* Customer segmentation
* Review and rating analysis
* Monthly revenue trends
* Average Order Value (AOV)

---

## 🗂️ Dataset

The ShopSphere dataset contains the following tables:

| Table         | Description                      |
| ------------- | -------------------------------- |
| `customers`   | Customer information             |
| `products`    | Product and category information |
| `orders`      | Order details                    |
| `order_items` | Products included in each order  |
| `payments`    | Payment information              |
| `reviews`     | Customer product reviews         |

---

## 🛠️ Technologies Used

* **MySQL** — Database and SQL analysis
* **Python** — Data analysis
* **Pandas** — Data manipulation
* **Matplotlib** — Data visualization
* **SQLAlchemy** — MySQL-Python connection
* **Jupyter Notebook** — Analysis environment
* **Git & GitHub** — Project version control

---

## 📊 Analysis Performed

### Customer Analysis

* Customer distribution by city
* Monthly customer signups
* Customer spending analysis
* Customer segmentation
* Top customers by spending

### Sales Analysis

* Monthly order trends
* Delivered order analysis
* Top-selling products
* Category-wise sales
* City-wise revenue

### Product Analysis

* Products by category
* Category revenue
* Best-selling products
* Products without delivered sales
* Product ratings

### Payment Analysis

* Payment method usage
* Payment status analysis
* Payment success rate

### Revenue Analysis

* Total revenue
* Monthly revenue
* Revenue growth
* Average Order Value
* Monthly AOV

### Review Analysis

* Category-wise average ratings
* Published review analysis
* Top-rated products

---

## 📈 Visualizations

The project includes visualizations for:

* Customers by City
* Monthly Orders
* Order Status Distribution
* Products by Category
* Revenue by Category
* Payment Status Distribution
* Top 10 Best-Selling Products
* Top 10 Customers by Spending
* Monthly Revenue
* Customer Segmentation
* Category Ratings
* Revenue by City
* Payment Methods
* Monthly Revenue Growth
* Monthly Average Order Value

---

## 🔍 Key SQL Concepts Used

The project demonstrates practical use of:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `JOIN`
* `LEFT JOIN`
* Aggregate functions
* Subqueries
* CTEs
* `CASE`
* `ROW_NUMBER()`
* `LAG()`
* Date functions
* Revenue calculations

---

## 📁 Project Structure

```text
ShopSphere_Analytics/
│
├── ShopSphere_Analytics.sql
├── ShopSphere_Analytics_Sharvari.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1 — Database Setup

Open `ShopSphere_Analytics.sql` in MySQL Workbench and execute the script.

### Step 2 — Select Database

```sql
USE shopsphere;
```

### Step 3 — Open Jupyter Notebook

Open:

```text
ShopSphere_Analytics_Sharvari.ipynb
```

### Step 4 — Install Required Libraries

```bash
pip install pandas matplotlib sqlalchemy pymysql
```

### Step 5 — Run the Notebook

Run the notebook cells from top to bottom.

> Keep database credentials private. Do not upload passwords or other credentials to GitHub.

---

## 🎯 Project Outcome

This project demonstrates how SQL and Python can be combined to perform practical e-commerce data analysis.

The analysis provides insights into customer behaviour, product performance, sales trends, payment preferences, revenue patterns, and customer spending.

---

## 👩‍💻 Author

**Sharvari Patil**

B.Tech Computer Science & Engineering

### Tools & Technologies

`MySQL` `Python` `Pandas` `Matplotlib` `SQLAlchemy` `Jupyter Notebook` `GitHub`
