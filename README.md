# 🔧 Auto Mechanic Shop Database

A Microsoft Access-based relational database system designed for *AutoTrack*, an NYC auto repair shop. It manages customers, vehicles, services, parts, invoices, and employees in a streamlined, centralized environment.

---

## Purpose

- This database was created for *AutoTrack*, a growing auto mechanic shop in New York City, to replace inefficient manual recordkeeping with a modern digital solution. The system manages customer profiles, vehicle details, appointments, services, parts inventory, suppliers, invoices, and employee records. By centralizing these elements, the application reduces errors, streamlines operations, enables faster appointment scheduling, supports real-time inventory tracking, simplifies payroll, and ensures seamless billing and reporting — all while supporting the shop’s scalability and long-term growth.

---

## 📁 Project Structure

| Folder          | Contents                                        |
|-----------------|--------------------------------------------------|
| `documentation/`| Project report PDF, ER diagram                   |
| `forms/`        | MS Access data entry forms                       |
| `reports/`      | Access reports including wages and inventory     |
| `queries/`      | SQL query screenshots or files                   |
| `vba/`          | VBA formatting code for data validation          |

---

## 📄 Documentation

- [📄 Full Project Report (PDF)](documentation/Auto%20Mechanic%20Shop%20Database%20Project.pdf)
- ![Entity Relationship Diagram](documentation/Entity%20Relationship%20Diagram.png)

---

## 🗂️ MS Access Forms

| Form Name      | Screenshot |
|----------------|------------|
| Customer Form  | ![](forms/customer-data-entry_form.png) |
| Employee Form  | ![](forms/employee-data-entry_form.png) |
| Invoice Form   | ![](forms/invoice-data-entry_form.png) |
| Parts Form     | ![](forms/parts-data-entry_form.png) |
| Service Form   | ![](forms/service-data-entry_form.png) |
| Vehicle Form   | ![](forms/vehicle-data-entry_form.png) |

---

## 📑 Reports

| Report Name             | Screenshot |
|-------------------------|------------|
| Employee Wages Report   | ![](reports/employee-wages-report_form.png) |
| Total Inventory Report  | ![](reports/total-inventory-report_form.png) |
| Employee Service Report | ![](reports/employee-service-report_form.png) |

---

## 💻 Queries

Common SQL queries were used to retrieve and combine data across normalized tables. Example:

![Example Queries](queries/Example-Queries.png)

---

## 🧠 VBA Enhancements

Custom VBA functions were created to auto-format data:

| VBA Task            | Screenshot |
|---------------------|------------|
| Capitalize Names    | ![](vba/name_vba-code.png) |
| Format Job Title    | ![](vba/job-title_vba.png) |
| Format City & State | ![](vba/location_vba.png) |

---

## 🔒 Database Highlights

- Fully normalized to 3NF
- Custom navigation forms
- Parameterized queries
- Integrated reports for business decisions
- Input validation using VBA

---

## 🧾 Technologies Used

- Microsoft Access
- SQL 
- VBA
- Lucidchart

---
