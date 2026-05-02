# 📘 SQL WHERE & LIMIT Clauses (English ↔ Arabic)

This note explains the `WHERE` and `LIMIT` clauses with bilingual translations and examples.

---

### 🔹 WHERE Clause
- **English**: Filters rows based on a condition.  
- **Arabic**: **شرط التصفية**  
- **Example**:  
  ```sql
  SELECT * 
  FROM employees 
  WHERE salary > 5000;
  
### 🔹 LIMIT Clause
  English: Restricts the number of rows returned.
  Arabic: تحديد عدد الصفوف
  Example:
     sql

    SELECT * 
    FROM employees 
    LIMIT 10;
→ يعرض أول 10 صفوف فقط من جدول الموظفين
