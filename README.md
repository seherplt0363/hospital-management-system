



\# 🏥 Hospital Management System



A console-based Hospital Management System developed using \*\*Java, JDBC, and SQL Server\*\*.  

The project demonstrates a layered architecture with basic CRUD operations and database integration.



\---



\## 📌 Features



\- 👤 Patient Management

&#x20;   - Add Patient

&#x20;   - Update Patient

&#x20;   - Delete Patient

&#x20;   - Search Patient

&#x20;   - List Patients



\- 👨‍⚕️ Doctor Management

&#x20;   - Add Doctor

&#x20;   - List Doctors



\- 📅 Appointment Management

&#x20;   - Create Appointment

&#x20;   - List Detailed Appointments



\- 🔐 Data Validation

&#x20;   - Input validation (age, name, ID checks)

&#x20;   - Foreign key control (Patient / Doctor existence check)



\---



\## 🧱 Project Architecture



The project follows a simple layered architecture:





UI (MainMenu)

↓

Service Layer (Business Logic)

↓

DAO Layer (Database Access)

↓

SQL Server Database





\---



\## 🛠️ Technologies Used



\- Java (OOP)

\- JDBC

\- Microsoft SQL Server

\- IntelliJ IDEA / Eclipse



\---



\## 📂 Project Structure





src/

├── ui/ # User interface (Main menu)

├── services/ # Business logic layer

├── dao/ # Database access layer

├── model/ # Entity classes (Patient, Doctor, Appointment)

└── database/ # DB connection class





\---



\## ⚙️ How to Run



1\. Clone the repository:

```



git clone https://github.com/your-username/hospital-management-system.git



```



2\. Import project into your IDE (IntelliJ or Eclipse)



3\. Configure database connection in `DatabaseConnection.java`



4\. Run `MainMenu.java`



\---



\## 🗄️ Database Setup



\- Create a database in SQL Server (e.g. `HospitalDB`)

\- Run the provided SQL scripts (if available)

\- Ensure tables:

&#x20;   - Patients

&#x20;   - Doctors

&#x20;   - Appointments



\---





\## 👨‍💻 Author



\*\*Seher Polat\*\*  

Computer Engineering Student  

Java | SQL | Algorithms



\---

