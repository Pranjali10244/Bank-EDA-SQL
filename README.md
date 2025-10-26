## 🏦 MyBankDB – Bank Management Database Project

### 📘 Overview

**MyBankDB** is a structured SQL-based database project designed to manage and analyze key banking operations such as **customers, accounts, loans, credit cards, ATMs, and transactions**.
It demonstrates a real-world approach to data organization, financial analytics, and SQL query handling in a banking environment.

---

### 🧱 Database Structure

The database contains the following main tables:

1. **Customers** – Stores personal and demographic details of all customers.
2. **Accounts** – Contains account-related data like account type, balance, and status.
3. **Transactions** – Tracks deposits, withdrawals, transfers, and transaction details.
4. **Loans** – Manages loan information such as amount, start and end dates, and interest rates.
5. **CreditCards** – Holds information about card numbers, credit limits, and balances.
6. **Branches** – Represents bank branch locations and related details.
7. **ATMs** – Maintains data about ATM locations, operational status, and servicing details.

---

### ⚙️ Core Functionalities

#### 🔍 Data Retrieval and Exploration

* View complete data from all tables.
* Join multiple tables to get combined insights (e.g., customers with accounts or loans).

#### 📊 Data Analysis and Aggregation

* Total number of customers, accounts, and loans.
* Total credit limit and overall loan amount.
* Average customer age and average account balance.
* Calculate days remaining for loan repayment.

#### 🧮 Advanced SQL Queries

* Find second or fifth highest loan amount.
* Identify customers with multiple accounts.
* Categorize customers into **age groups** (Below 30, 30–60, Above 60).
* Retrieve transactions, accounts, or loans filtered by date or status.
* Extract odd-numbered rows, substring of names, and separate first and last names.

#### 🏦 Financial Insights

* Analyze monthly transactions per account.
* Detect credit cards exceeding their credit limits.
* Calculate loan attrition and overdue durations.
* Retrieve the latest transaction for each account.
* Assess inactive ATMs per branch location.

---

### 🧠 Learning Outcomes

By working on **MyBankDB**, you’ll learn how to:

* Design and implement **normalized relational databases**.
* Use **aggregate, conditional, and date-based SQL functions**.
* Write **joins and subqueries** for real-world business scenarios.
* Apply **data manipulation** (insertion, deletion, and updates).
* Derive actionable business insights using SQL queries.

---

### 🧩 Technologies Used

* **Database System:** MySQL
* **Key SQL Concepts:**

  * Aggregate functions (`COUNT`, `SUM`, `AVG`)
  * Joins (`INNER`, `LEFT`, `RIGHT`)
  * Subqueries and nested queries
  * String and Date functions
  * Conditional statements (`CASE`, `IF`, etc.)

---

### 🚀 Future Enhancements

* Add **triggers** for automatic transaction logging.
* Create **stored procedures** for common banking operations.
* Implement **data visualization dashboards** using Power BI or Tableau.
* Introduce **user roles and permissions** for enhanced data security.
