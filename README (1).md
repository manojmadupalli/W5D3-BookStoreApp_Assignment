# 📘 Student Assignment Style (Simple & Concise)

## BookStore Application

### Overview
This project is a **BookStore Management Application** built using **ASP.NET Core**.  
It allows managing books, customers, and orders with database integration.

### Contents
- `BookStoreApp/` → Main ASP.NET Core application  
- `BookStoreDataBase.sql` → SQL script to create the database  

### Requirements
- .NET 9 SDK  
- SQL Server  

### Setup & Run
1. Clone or extract the project.  
2. Open `BookStoreApp.sln` in **Visual Studio / VS Code**.  
3. Run the SQL script `BookStoreDataBase.sql` in SQL Server to create the database.  
4. Update **`appsettings.json`** with your SQL connection string.  
5. Build and run the project:  
   ```bash
   dotnet run
   ```

### Output
The application will start on `https://localhost:5009` (or a similar port).  
You can access the BookStore UI in your browser.

---

# 💼 Professional Style (Detailed GitHub-Ready)

## 📚 BookStore Application

A full-stack **BookStore Management System** built with **ASP.NET Core (.NET 9)** and **SQL Server**.  
This project demonstrates a layered architecture for managing books, users, and transactions.

---

## 🚀 Features
- 📖 Manage books (add, update, delete, view)  
- 👥 Manage users/customers  
- 🛒 Shopping cart & order system  
- 🔐 Role-based authentication & authorization  
- 💾 SQL Server database integration  

---

## 🛠 Tech Stack
- **Backend:** ASP.NET Core (.NET 9)  
- **Database:** SQL Server  
- **ORM:** Entity Framework Core  
- **Frontend:** Razor Pages (or MVC Views)  
- **Tools:** Visual Studio 2022 / VS Code  

---

## 📂 Project Structure
```
W5_Day3_Assignment/
│
├── W5 Day 3 Daily coding assignment/
│   ├── BookStoreDataBase.sql      # SQL script for DB schema
│   ├── BookStoreApp/              # ASP.NET Core application
│   │   ├── appsettings.json       # Config file (update DB connection string here)
│   │   ├── Program.cs             # Application startup
│   │   ├── BookStoreApp.csproj    # Project file
│   │   └── bin/                   # Build output
```

---

## ⚙️ Setup Instructions

### 1. Prerequisites
- Install **.NET 9 SDK**
- Install **SQL Server**
- Install **Visual Studio 2022** or **VS Code**

### 2. Database Setup
1. Open SQL Server Management Studio (SSMS)  
2. Run the script:  
   ```sql
   BookStoreDataBase.sql
   ```
3. This will create the required database and tables.

### 3. Configure App
Update `BookStoreApp/appsettings.json` with your SQL connection string:
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=BookStoreDB;Trusted_Connection=True;MultipleActiveResultSets=true"
}
```

### 4. Run Application
```bash
cd "BookStoreApp"
dotnet run
```
Application will run on:
```
http://localhost:5009
```

---

## Output 

![Output 1 - Main HomePage of BookStoreApp](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 1.png>)

![Output 2 - Full info of Book](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 2.png>)

![Output 3 - Creating a Book](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 3.png>)

![Output 4 - New Book info Added](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 4.png>)

![Output 5 - Deleting the Book ](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 5.png>)

![Output 6 - Final HomePage after Updation](<W5 Day 3 Daily coding assignment/W5 Day 3 Daily coding assignment/Output 6.png>)
----

## ✅ Future Enhancements
- Add JWT authentication  
- Implement API endpoints for external integrations  
- Enhance UI with Angular/React frontend  

---

## 👨‍💻 Author : Manoj Madupalli
Developed as part of **W5 Day 3 Daily Coding Assignment**.
