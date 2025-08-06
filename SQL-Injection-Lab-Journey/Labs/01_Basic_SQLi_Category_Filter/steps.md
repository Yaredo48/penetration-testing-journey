# ✅ Step-by-Step: Solving SQL Injection in Category Filter using Burp Suite

This lab demonstrates a basic SQL Injection vulnerability in a product category filter. The objective is to exploit the SQL query to display **unreleased products**.

---

## 🧠 Target Query Behind the Application

When you click on a product category like "Gifts", the application sends a query like:

```sql
SELECT * FROM products WHERE category = 'Gifts' AND released = 1
