Automobile Management System
📌 Project Overview
The Automobile Management System is a database-driven application designed for managing the operations of an automobile service center (e.g., Honda Service Center). The system provides separate logins for customers and administrators, enabling digital management of vehicle service details, customer records, billing, and staff operations.
It improves operational efficiency by replacing manual record-keeping with a structured Database Management System (DBMS).
🎯 Problem Statement
Vehicle owners often face delays and inefficiencies due to manual processes in traditional service centers. Daily tasks such as entering customer records, tracking vehicle repairs, generating bills, and maintaining service history are time-consuming when done manually.
This project solves the issue by:
Digitalizing workflows of the automobile service center.
Reducing response time to customer queries.
Improving accuracy in billing, employee management, and record keeping.
🔑 Features
👤 Customer
Register/Login securely.
Add multiple vehicles.
Choose services (general or fault-specific).
View complete service history.
Get instant bills (free or paid depending on insurance).
🛠 Administrator
Manage all customer and service records.
Update service costs, employee salary, and offers.
Assign employees to service tasks.
Maintain records of spares, faults, and transactions.
Monitor all operations via the database.
🗄 Database Schema
Database Name: Service_Centre_db
Tables:
auto_man – Manufacturer details
auto_show – Showroom details
ser_center – Service center details
employees – Employee details
cus – Customer details
spares – Spare parts and pricing
fault – Vehicle faults and repairs
vehicle – Vehicle details (model, insurance, etc.)
bill – Service billing details
transaction – Payment and transaction history
🏗 ER Diagram
(Add your ER diagram image here, e.g. ![ER Diagram](er-diagram.png))
📊 Example Tables
Vehicle Table
v_id	v_no	v_model	v_price	v_dom	c_id	sr_id	sc_id	v_insurance
101	TN23AB1234	Honda City	1200000	2020-05-01	C01	SR01	SC01	Yes
Bill Table
b_no	b_date	b_amt	f_id	v_id	e_id	c_id	sc_id
501	2023-07-15	3500	F01	101	E01	C01	SC01
⚙️ Tech Stack
Database: MySQL
Backend: PHP
Frontend: HTML, CSS
Tools: XAMPP / MySQL Workbench
