
# 🚗 DVLD System – Driver and Vehicle License Department

A comprehensive **Driver and Vehicle License Department (DVLD)** management system that handles driver's license issuance, testing processes, and administrative operations. Built using **.NET Framework Windows Forms** and follows a **3-tier architecture**.

---

## 📁 Project Structure

DVLD-System/

├── DVLD.PL/ # Presentation Layer (UI)

├── DVLD.BLL/ # Business Logic Layer

├── DVLD.DAL/ # Data Access Layer

├── DVLD.PL.sln # Solution File

└── README.md


## 🚀 Getting Started

### ✅ Prerequisites

- **Operating System:** Windows 10 or newer
- **IDE:** Visual Studio 2019 or later
- **Database:** SQL Server
- **Framework:** .NET Framework 4.7.2 or higher

### ⚙️ Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/mohamedelsawah345/DVLD-System.git
Open Solution:

Open DVLD.PL.sln in Visual Studio.

Configure Database:

Create a SQL Server database.

Run the provided SQL scripts (tables, stored procedures, etc.).

Update your web.config file with the correct connection string.

Run the Project:

Press F5 or click Start in Visual Studio.

🧱 System Architecture
PL (Presentation Layer): Manages all user interface components.

BLL (Business Logic Layer): Contains the system's core logic and rules.

DAL (Data Access Layer): Responsible for database operations.

PL (Presentation Layer): Contains all ASP.NET UI logic (Web Forms).

BLL (Business Logic Layer): Core logic such as exam processing, license tracking.

DAL (Data Access Layer): CRUD operations and SQL interaction

🔑 Features
📇 License Management
Register new driving licenses

View and update license details

Suspend or revoke licenses

🧪 Test Management
Schedule theory & practical tests

Track test results for each applicant

Test history and re-exam process

👤 Applicant Management
Add, edit, delete applicants

View applicant profiles and status

🛠️ Admin Features
Manage users and roles

Authentication via login page

Session-based access control

👤 User & Driver Management
Add, Edit, Delete Drivers

Manage user accounts and roles

📝 Exam Management
Schedule theory and practical exams

Record exam results

Generate reports and pass/fail history

🚘 License Issuing
Issue licenses upon exam success

Manage license renewal and expiration

License types and categories supported

🧾 Database
Built on SQL Server

Includes normalized tables for applicants, licenses, tests, users

Uses stored procedures for secure and efficient queries

🔐 Security
Login system with session handling

Server-side validation

Connection string configuration

![carrent](https://github.com/user-attachments/assets/c7503286-4a72-43a1-b486-aa8a1b0d64b3)


📄 License
Licensed under the MIT License.

✍️ Author
Mohamed Elsawah


