# 🧪 Lab 01: SQL Injection in Category Filter

**Goal**: Display unreleased products by exploiting SQL injection in the category filter.

**Vulnerability Location**: URL parameter `category`

**Challenge**: The backend SQL query is:
```sql
SELECT * FROM products WHERE category = 'Gifts' AND released = 1
