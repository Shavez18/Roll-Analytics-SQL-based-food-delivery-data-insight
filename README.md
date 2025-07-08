
# 🥖 Roll Analytics – SQL-Based Food Delivery Data Insights

## 📘 Project Overview

This project simulates a food delivery business that offers customizable rolls. It uses SQL to perform end-to-end analysis of customer orders, roll compositions, driver performance, and delivery metrics. The aim is to extract actionable insights from structured relational data, demonstrating strong SQL skills, data modeling, and business thinking.

---

## 🗂️ Project Structure

| Table Name         | Description |
|--------------------|-------------|
| `customer_orders`  | Records of each roll ordered by customers |
| `driver_order`     | Delivery and pickup records, including cancellations |
| `driver`           | Driver details and registration dates |
| `rolls`            | Roll types (Veg / Non-Veg) |
| `rolls_recipes`    | Ingredients mapping per roll |
| `ingredients`      | List of available roll ingredients |

---

## 🧠 Key Business Questions Answered

- 📌 How many total rolls were ordered?
- 📌 What is the number of unique customers?
- 📌 How many successful deliveries were made by each driver?
- 📌 What are the most popular roll types and ingredients?
- 📌 What are the peak hours and days for orders?
- 📌 How do cancellations affect order flow?
- 📌 Which customer ordered the most rolls?

---

## 🧪 SQL Features Used

- `JOIN`, `GROUP BY`, `DISTINCT`, `CASE`, `RANK()`, `DATEPART`, `DATENAME`
- Nested subqueries and aggregate functions
- Handling of messy data (`NaN`, `null`, blanks)
- Time-based and category-based segmentation

---





## 🛠️ Getting Started

1. Clone this repo.
2. Import the SQL scripts into your database (SQL Server, PostgreSQL, or MySQL).
3. Run the analysis queries in the provided `.sql` file or use your SQL IDE.
4. Explore the results in the query console or build visualizations.

---

## 📌 Insights Example

- Most orders occur between **6 PM – 8 PM**.
- **Non-Veg Rolls** are more popular among repeat customers.
- **Driver 1** has the highest successful delivery rate.
- **Cheese**, **Chicken**, and **Schezwan Sauce** are top ingredients.

---

## ✅ What I Learned

- Designing normalized SQL schemas
- Writing production-ready SQL queries
- Business insight extraction from transactional data
- Data cleaning within SQL

---




