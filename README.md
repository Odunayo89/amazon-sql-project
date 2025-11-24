# 🛒 Amazon Product Insights and SQL Analysis Using PostgreSQL

This project demonstrates end-to-end SQL analysis of real-world e-commerce data from Amazon India using PostgreSQL.  
It includes data cleaning, transformation, aggregation, window functions, subqueries, CTEs, ranking logic, and analytical insights.

---

## 📦 Dataset Description

The dataset contains ~9,300 Amazon product records with:

- **Product_Name** – product title including brand + model  
- **Price** – listed selling price  
- **Rating** – average customer rating (1–5 scale)  
- **Review_Count** – number of customer reviews  
- **ASIN** – unique product identifier  
- **Product_URL** – product link  
- **Availability** – In Stock / Out of Stock  

---

## 🧠 Skills Demonstrated

- Data cleaning with `COALESCE`, `NULLIF`, `TRIM`
- String parsing using `split_part()`
- Aggregations (`AVG`, `SUM`, `COUNT`)
- Conditional logic using `CASE`
- Window functions (`RANK()`, PARTITION BY)
- CTEs for reusable logic
- Subqueries and correlated subqueries
- Join operations (INNER, FULL)
- Performance analysis using `EXPLAIN`

---

## 📁 Project Structure
