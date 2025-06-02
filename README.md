# 🍕 Pizza Sales Data Analysis using SQL

This project explores sales data for a pizza business using **SQL queries** to derive actionable insights. By performing various analysis tasks—such as calculating revenue, identifying best-selling pizzas, and examining ordering trends—this project demonstrates the power of SQL in business analytics.

---

## 📌 Objective

- Analyze pizza order data to uncover trends and business opportunities.
- Understand sales performance by category, pizza type, and time.
- Deliver valuable insights that can help improve operations and customer satisfaction.

---

## 🗃️ Dataset Overview

The database consists of the following key tables:

- `orders` – Contains order date and time
- `order_details` – Quantity and item information per order
- `pizzas` – Pizza size, price, and ID
- `pizza_types` – Name, category, and description of each pizza type

---

## 🔍 Key Analysis Performed

1. **Total Orders**  
   - Counted the total number of orders placed.

2. **Total Revenue**  
   - Calculated total sales by multiplying quantity and price.

3. **Top Performers**
   - Identified the highest-priced pizza.
   - Found the most ordered pizza types (by quantity and revenue).
   - Determined the most common pizza size.

4. **Category Analysis**
   - Category-wise quantity sold and distribution of pizza types.

5. **Time-Based Trends**
   - Analyzed order volume by hour to detect peak times.
   - Calculated average pizzas ordered per day.

---

## 📈 Recommendations (as a Data Analyst)

- **Stock Popular Sizes**: Medium and large pizzas are ordered the most—ensure inventory reflects this.
- **Promote High-Revenue Pizzas**: Focus marketing on top 3 revenue-generating pizzas.
- **Time-Based Offers**: Consider offering time-based discounts during non-peak hours.
- **Menu Optimization**: Reevaluate underperforming pizza categories to streamline the menu.
- **Category Promotions**: Use category-wise data to design combo offers or targeted ads.

---

## 🧠 Skills & Concepts Gained

- **SQL Joins** to combine multiple related tables  
- **Aggregate Functions** like `SUM()`, `COUNT()`, `AVG()`  
- **Grouping and Filtering** using `GROUP BY`, `ORDER BY`, `LIMIT`  
- **Subqueries** for nested logic  
- **Datetime Functions** to analyze time-based trends  
- **Revenue Calculation** by multiplying quantity with price  
