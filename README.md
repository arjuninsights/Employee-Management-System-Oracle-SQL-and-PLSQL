# 👨‍💼 Employee Management System

A complete **Employee Management System** developed using **Oracle SQL** and **PL/SQL** to manage employee records, department management, salary processing, audit logging, and performance optimization.

---

# 🚀 Technologies Used

- Oracle SQL
- PL/SQL
- Stored Procedures
- Functions
- Packages
- Triggers
- Cursors
- BULK COLLECT
- FORALL
- Exception Handling
- Indexing & Performance Tuning

---

# ✨ Key Features

## 🔹 Employee Management

- Add and manage employee records
- Department-wise employee management
- Employee status handling (`ACTIVE / INACTIVE`)
- Employee information retrieval

---

## 🔹 Salary Management

- Annual salary calculation
- Bulk salary increment by department
- Salary update automation

---

## 🔹 Advanced PL/SQL Features

- PL/SQL Packages for modular programming
- Stored Procedures and Functions
- Cursor-based employee search
- Triggers for automatic audit logging
- Exception handling using `WHEN OTHERS`
- Bulk processing using `BULK COLLECT` and `FORALL`

---

## 🔹 Database Validations

- Duplicate employee ID prevention
- Foreign key validation for departments
- Error handling and validation mechanisms

---

## 🔹 Performance Optimization

- Indexed columns for faster query execution
- Optimized SQL queries
- Efficient bulk update processing

---

## 🔹 Audit & Monitoring

- Automatic audit trail for employee operations
- Tracks INSERT, UPDATE, and DELETE operations
- Employee activity monitoring

---

# 📂 Database Objects

## 🗄️ Tables

- Departments
- Employees
- Employee_Audit

---

## ⚙️ PL/SQL Objects

- Procedures
- Functions
- Packages
- Triggers
- Cursors
- Indexes

---

# 🔧 Modules Included

| Module | Description |
|--------|-------------|
| Employee Management | Manage employee records |
| Department Management | Handle employee departments |
| Salary Management | Process salary calculations |
| Bulk Salary Update | Department-wise salary increment |
| Audit Logging | Store employee activity logs |
| Employee Search | View employee details |
| Performance Optimization | Faster query execution using indexes |

---

# 📈 Advanced Features

- Automatic audit logging using triggers
- Bulk salary update using `BULK COLLECT` and `FORALL`
- Cursor-based employee retrieval
- Indexed columns for performance tuning
- Exception handling for duplicate employee records
- Optimized SQL queries for faster execution
- Department-based employee management

---

# 💡 Learning Outcomes

- Real-world PL/SQL project development
- Database design and relationship management
- Writing modular PL/SQL code using packages
- Performance tuning using indexes
- Bulk data processing techniques
- Trigger-based audit logging
- Advanced exception handling techniques

---

# ▶️ Sample Operations

## 👨‍💼 Add Employee

```sql
BEGIN
    add_employee(101,'Arjun Kumar',50000,2);
END;
/
