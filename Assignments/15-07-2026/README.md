# SQL Joins Assignments

## 📌 Overview
This folder contains SQL assignments focused on different types of SQL joins. These exercises helped me understand how data from multiple tables can be combined based on matching or non-matching records.

## 📂 Folder Structure

```
Assignments
└── 📁 15-07-2026
    ├── 📄 01_Inner_Join.sql
    ├── 📄 02_Left_Join.sql
    ├── 📄 03_Right_Join.sql
    ├── 📄 04_Full_Join.sql
    ├── 📄 05_Left_Anti_Join.sql
    ├── 📄 06_Right_Anti_Join.sql
    └── 📄 07_Full_Anti_Join.sql
```

## 📖 Topics Covered

### 1. Inner Join
- Returns only the matching records from both tables.
- Used to retrieve related data based on a common column.

### 2. Left Join
- Returns all records from the left table.
- Returns matching records from the right table.
- Non-matching rows from the right table contain `NULL` values.

### 3. Right Join
- Returns all records from the right table.
- Returns matching records from the left table.
- Non-matching rows from the left table contain `NULL` values.

### 4. Full Join
- Returns all matching and non-matching records from both tables.
- Missing values are represented as `NULL`.

### 5. Left Anti Join
- Returns records that exist only in the left table.
- Excludes rows that have matching values in the right table.

### 6. Right Anti Join
- Returns records that exist only in the right table.
- Excludes rows that have matching values in the left table.

### 7. Full Anti Join
- Returns records that do not have matching values in either table.
- Displays only the unmatched records from both tables.

## 🎯 Learning Outcomes

After completing these assignments, I learned:

- How different SQL joins work.
- When to use each type of join.
- How to combine data from multiple tables.
- How to retrieve matching and non-matching records.
- How `NULL` values appear in join operations.
- The practical difference between Inner, Left, Right, Full, and Anti Joins.

## 🛠️ Technologies Used

- SQL
- MySQL / PostgreSQL (Standard SQL syntax)

## 📌 Note

These assignments were completed as part of my SQL learning journey to strengthen my understanding of relational databases and join operations.
