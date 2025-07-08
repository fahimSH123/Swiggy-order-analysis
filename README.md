# Swiggy-order-analysis
The project shows how to get practical insights like top-selling cities, best-rated restaurants, most popular food types, and highest average order value — all with simple, readable queries.

# 🍽️ Swiggy-Style SQL Mini Project

This mini SQL project analyzes a Swiggy-like food delivery dataset to answer **5 real-world business questions**.  
It helped me practice practical SQL skills like `GROUP BY`, `HAVING`, window functions, `PARTITION BY`, `RANK()`, CTEs, and fixing common subquery issues.

---

## 🔍 **Project Description**

In this project, I focused on translating raw order data into actionable insights — just like a business analyst would do for a real food delivery company.

**Problems I tackled:**
- Understanding when to use `GROUP BY` vs. `WHERE` vs. `HAVING`
- Using `PARTITION BY` with window functions to rank and segment data correctly
- Debugging `LIMIT` + subquery errors and solving them with `JOIN` logic
- Practicing `CTEs` to structure complex queries more clearly

---

## ✅ **The 13 Business Questions**

1️⃣ Top 5 cities by total sales and their average sales value 
2️⃣ Which restaurant generated the most revenue overall 
3️⃣ Top 5 food types by total sales
4️⃣ Restaurants with the highest average ratings with at least X total ratings 
5️⃣ Which restaurant has the highest average order value
6️⃣ Top 10 customers by total spend
7️⃣ Average number of orders per day
8️⃣ Which customer ID has the fastest average delivery time
9️⃣ Which area has the slowest average delivery time
🔟 Rank restaurants by total sales within each city (window function)
1️⃣1️⃣ Top 5 highest value orders
1️⃣2️⃣ Find the top order amount per customer (using JOINs and window functions separately)
1️⃣3️⃣ Segment customers based on total spend (Premium, Regular, Low)


---

## ⚡️ **Key SQL Concepts Practiced**

- `GROUP BY` + `HAVING` for conditional aggregation
- Window functions: `RANK()`, `ROW_NUMBER()`, `PARTITION BY`
- `ORDER BY` + `LIMIT` for top-N analysis
- Using `JOIN` to fix subquery `LIMIT & IN` issues
- Using `CTEs` for better query structure and reusability

---
Link to refer -->
