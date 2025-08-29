
# Employee Management System

A **Console-based application** built using **.NET (C#)** and **SQL Server** to manage employee records, calculate salaries, and generate reports. This system ensures **data persistence**, **easy salary computation**, and **structured employee management** with relational database support.

---

## 📌 Features

* Add, update, delete, and view employee records
* Maintain employee details in a relational database
* Calculate salaries with allowances, deductions, and hourly wages
* Generate structured payroll reports
* Ensure **data persistence** using SQL Server
* Console-based interface for easy interaction

---

## 🛠️ Tech Stack

* **Language:** C# (.NET)
* **Database:** SQL Server
* **Architecture:** Console-based application with relational database

---

## 📂 Database Schema

### **Employees Table**

* EmpId (Primary Key)
* EmpName
* Department
* Type (Permanent / Contract)

### **Payroll Table**

* PayrollId (Primary Key)
* BasicPay
* Allowance
* Deductions
* Hours
* HourlyRate
* Salary
* PaymentDate

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/employee-management-system.git
   ```
2. Open the project in **Visual Studio**.
3. Configure the **SQL Server connection string** in `appsettings.json` or inside your code.
4. Run the SQL scripts provided in the `/Database` folder to create tables.
5. Build and run the project.

---

## 📊 Future Enhancements

* Add user authentication
* Implement role-based access (Admin / Employee)
* Export salary reports to PDF/Excel
* Add a graphical user interface (GUI)

---

## 📜 License

This project is licensed under the MIT License.

---

