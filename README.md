# 💻 SQL Intermediate Querying Assignment

## 📌 Project Overview
This project is based on SQL intermediate concepts like filtering, sorting, aggregation, grouping, and joins 🔍.  
The dataset represents a real-world 🛒 e-commerce system including customers, orders, products, and order details.

---

## 🗂️ Database Tables Used
- 👤 customers   
- 📦 orders  
- 🧾 order_details  
- 🛍️ products  

---

## ✅ Task 1: Filtering and Sorting
- 🚫 Used `NOT IN` to exclude UAE and UK customers  
- 🔄 Applied multiple sorting:
  - 🌍 country (ascending)
  - 🔤 customer_name (descending)

---

## ✅ Task 2: Aggregation and HAVING
- 📊 Grouped customers by country  
- 🔢 Counted number of customers using `COUNT()`  
- ⚙️ Used `HAVING` to filter groups with more than 5 customers  
- ⬇️ Sorted results in descending order  

> ℹ️ Note: Due to limited sample data, no results were returned for this condition.

---

## ✅ Task 3: Join and Revenue Calculation
- 🔗 Joined `order_details` and `products` tables  
- 💰 Calculated revenue using:
  ```
  quantity × unit_price
  ```
- 📂 Grouped results by category  
- 🎯 Filtered categories with revenue > 1000  

> ℹ️ Note: Due to limited data, no category met this condition.

---

## 🧠 Key Learnings
- ⚖️ Difference between `WHERE` and `HAVING`  
- 📊 Use of `GROUP BY` and aggregate functions  
- 🔗 Importance of `JOIN` in combining tables  
- 🔄 Sorting using multiple columns  

---

## 🚀 Conclusion
This assignment helped me understand real-world SQL queries used in data analysis 📈, especially in e-commerce scenarios 🛍️. It improved my understanding of data filtering, aggregation, and joins.

---

## 📎 Submission
✅ All queries are tested and working as expected  
📌 Output may vary due to sample data limitations

---

## Submitted By: Keshav Kaushik
B.Sc Computer Science (2nd Year)
