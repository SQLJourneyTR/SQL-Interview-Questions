# Day 01 - Second Highest Salary

## 📌 Problem

Write a SQL query to find the **second highest salary** from the `Employee` table.

---

## 📂 Files

| File | Description |
|------|-------------|
| `schema.sql` | Creates the required table |
| `sample_data.sql` | Inserts sample records |
| `solution.sql` | SQL solution |
| `README.md` | Problem description and explanation |

---

## 🚀 How to Run

### Step 1

Run `schema.sql`

### Step 2

Run `sample_data.sql`

### Step 3

Run `solution.sql`

---

## 📊 Sample Data

| id | salary |
|----|--------|
| 1 | 100 |
| 2 | 200 |
| 3 | 300 |

---

## ✅ Expected Output

| SecondHighestSalary |
|---------------------|
| 200 |

---

## 💡 Explanation

The query first finds the highest salary.

Then it returns the maximum salary that is lower than the highest salary using a subquery.

---

## 🧠 SQL Concepts

- MAX()
- Aggregate Functions
- Subqueries
- WHERE Clause

---

## 💬 Interview Tip

This question is commonly asked in SQL interviews to test your understanding of aggregate functions and subqueries.

**Difficulty:** ⭐ Easy

---

⭐ Part of my **100 Days of SQL Interview Questions** challenge.
