# Expence Tracker


# 💰 Expense Tracker System (CashPilot)

A responsive web application built using **ASP.NET Core MVC**, **Entity Framework Core (Code First)**, and **SQL Server** to help users track personal income and expenses with a clean dashboard and intuitive UI.

---

## 📌 Live Preview

You can run this project locally to explore all features including dashboard analytics and transaction management.

---

## 🚀 Features

### 📊 Dashboard
- Displays **Total Income**, **Total Expenses**, and **Balance**
- Shows **recent transactions** (last 10)
- Includes **interactive charts** for visual financial analysis

### 🗂 Category Management
- Add, edit, and delete expense categories
- Categorize expenses for better tracking

### 💵 Transaction Management
- Full CRUD for income and expense transactions
- Handles hundreds of records efficiently

### 🏗 MVC Architecture
- Clean implementation of **Model–View–Controller** pattern
- Uses **Entity Framework Core Code First** with SQL Server

---

## 🛠 Tech Stack

| Feature | Tech Used |
|--------|------------|
| Backend | ASP.NET Core MVC |
| ORM | Entity Framework Core Code First |
| Database | SQL Server |
| Frontend | HTML, CSS, Bootstrap, Razor Views |
| Charts | Syncfusion UI |
| Tools | Visual Studio, SQL-Server, Git & GitHub |

---

## 📁 Project Structure

Expence-Tracker/
│
├── Controllers/
├── Models/
├── Views/
├── Data/
├── wwwroot/
│ ├── css/
│ └── js/
└── Program.cs


---

## ⚙️ Setup & Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/ParagWeb7/Expence-Tracker.git

2. Open in Visual Studio
Open the solution file in Visual Studio
Make sure .NET 7 SDK (or latest .NET Core) is installed

3. Configure Database
Update your appsettings.json with your SQL Server connection string:
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=ExpenseTrackerDB;Trusted_Connection=True;"
}

4. Run Migrations (Code First)
In Package Manager Console:
Add-Migration InitialCreate
Update-Database

5. Run the App
Press F5 or click Run.

🧑‍💻 Author:-

Parag Kotkar 💻🐱‍👤
GitHub: https://github.com/ParagWeb7
LinkedIn: https://www.linkedin.com/in/parag-kotkar-bca
