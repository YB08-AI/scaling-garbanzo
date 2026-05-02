# 📘 SQL JOIN Types (English ↔ Arabic)

This note explains the different types of SQL JOINs with bilingual translations and examples.

---

| SQL JOIN Type        | English Meaning | Arabic Translation | Example |
|----------------------|-----------------|--------------------|---------|
| `INNER JOIN`         | Returns rows where there is a match in both tables | **الربط الداخلي** | `SELECT * FROM A INNER JOIN B ON A.id = B.id;` → يعرض الصفوف المشتركة بين الجدولين |
| `LEFT JOIN` (LEFT OUTER JOIN) | Returns all rows from the left table, and matched rows from the right table | **الربط الخارجي الأيسر** | `SELECT * FROM A LEFT JOIN B ON A.id = B.id;` → يعرض كل صفوف الجدول الأيسر مع المطابقات من الجدول الأيمن |
| `RIGHT JOIN` (RIGHT OUTER JOIN) | Returns all rows from the right table, and matched rows from the left table | **الربط الخارجي الأيمن** | `SELECT * FROM A RIGHT JOIN B ON A.id = B.id;` → يعرض كل صفوف الجدول الأيمن مع المطابقات من الجدول الأيسر |
| `FULL JOIN` (FULL OUTER JOIN) | Returns all rows when there is a match in one of the tables | **الربط الخارجي الكامل** | `SELECT * FROM A FULL JOIN B ON A.id = B.id;` → يعرض كل الصفوف من كلا الجدولين سواء كانت مطابقة أم لا |

---

## 🧩 Quick Notes
- **INNER JOIN** → Only overlapping data.  
- **LEFT JOIN** → Everything from the left, plus matches.  
- **RIGHT JOIN** → Everything from the right, plus matches.  
- **FULL JOIN** → Everything from both, matched or not.  

---


------------------------------------------------------------------------


 **vertical list format**
---

# 📘 SQL JOIN Types (English ↔ Arabic)

### 🔹 INNER JOIN  
- **English**: Returns rows where there is a match in both tables.  
- **Arabic**: **الربط الداخلي**  
- **Example**:  
  ```sql
  SELECT * 
  FROM A INNER JOIN B 
  ON A.id = B.id;
  ```
  → يعرض الصفوف المشتركة بين الجدولين  

---

### 🔹 LEFT JOIN (LEFT OUTER JOIN)  
- **English**: Returns all rows from the left table, and matched rows from the right table.  
- **Arabic**: **الربط الخارجي الأيسر**  
- **Example**:  
  ```sql
  SELECT * 
  FROM A LEFT JOIN B 
  ON A.id = B.id;
  ```
  → يعرض كل صفوف الجدول الأيسر مع المطابقات من الجدول الأيمن  

---

### 🔹 RIGHT JOIN (RIGHT OUTER JOIN)  
- **English**: Returns all rows from the right table, and matched rows from the left table.  
- **Arabic**: **الربط الخارجي الأيمن**  
- **Example**:  
  ```sql
  SELECT * 
  FROM A RIGHT JOIN B 
  ON A.id = B.id;
  ```
  → يعرض كل صفوف الجدول الأيمن مع المطابقات من الجدول الأيسر  

---

### 🔹 FULL JOIN (FULL OUTER JOIN)  
- **English**: Returns all rows when there is a match in one of the tables.  
- **Arabic**: **الربط الخارجي الكامل**  
- **Example**:  
  ```sql
  SELECT * 
  FROM A FULL JOIN B 
  ON A.id = B.id;
  ```
  → يعرض كل الصفوف من كلا الجدولين سواء كانت مطابقة أم لا  

---
