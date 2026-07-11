# Day 01 - Second Highest Salary

## 🎯 Problem

Write a SQL query to find the **second highest salary** from the `Employee` table.

---

## 📋 Example

### Employee

| id | salary |
|----|--------|
| 1 | 100 |
| 2 | 200 |
| 3 | 300 |

### Expected Output

| SecondHighestSalary |
|---------------------|
| 200 |

---

## 💡 Approach

This solution uses a subquery to find the highest salary first, then returns the maximum salary that is lower than it.

---

## 🛠️ SQL Concepts

- Aggregate Functions
- MAX()
- Subquery
- WHERE Clause

---

## 📄 Solution

The SQL solution is available in the `solution.sql` file.

---

## 📚 What I Learned

- How to use the `MAX()` function
- How subqueries work
- How to filter data using the `WHERE` clause

---

⭐ Part of my **100 Days of SQL Interview Questions** challenge.
