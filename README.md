# 🍽️ Recipe Web API

A **.NET 8 Web API** following **Onion Architecture** with **EF Core, Dapper, and Repository Pattern**, designed to manage recipes, categories, and ingredients efficiently.

---
🔍 Key Features
✅ Onion Architecture (Separation of Concerns)
✅ Entity Framework Core with Repository Pattern
✅ Dapper for optimized queries
✅ Dependency Injection (DI) Implementation
✅ Data Validation with Fluent Validation (Optional)
✅ Logging with Serilog (Optional)
✅ JWT Authentication (Optional)
✅ Swagger Documentation
---
---
## 📌 Table of Contents
- [Setup](#setup)
- [Run the API](#run-the-api)
- [API Endpoints](#api-endpoints)
- [Key Features](#key-features)
- [Contributing](#contributing)
- [License](#license)
---

## 🛠 Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/RecipeAPI.git
cd RecipeAPI

2️⃣ Setup Database
Update appsettings.json with your SQL Server Connection String.
Run EF Core Migrations:
```sh
dotnet ef migrations add InitialCreate --project RecipeAPI.Infrastructure --startup-project RecipeAPI.API
dotnet ef database update --project RecipeAPI.Infrastructure --startup-project RecipeAPI.API

🚀 Run the API
```sh
cd RecipeAPI.API
dotnet run

Open Swagger UI at: http://localhost:5000/swagger/index.html



This README is **GitHub-ready** and provides a structured, clear guide for **setup, API usage, and contributions**. Let me know if you need modifications! 🚀
