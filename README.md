# 🔐 DynamicDatabaseConnection

**Secure & Environment-Driven Database Configuration for .NET Projects using Clean Architecture**

This repository provides a robust and flexible way to manage database connection strings dynamically in ASP.NET Core applications. Instead of hardcoding values in `appsettings.json`, connection strings are built at runtime using **environment variables**, ensuring security, configurability, and compatibility with **Clean Architecture** principles.

---

## ✅ Features

- 🔐 **Environment-Based Security**: Load database configuration from environment variables (e.g., Docker, Azure, local `.env`).
- 🧱 **Clean Architecture Friendly**: Keeps infrastructure concerns out of application and domain layers.
- 🛠 **Supports SQL & Windows Auth**: Dynamically constructs connection strings based on availability of credentials.
- ☁️ **Cloud & CI/CD Ready**: Ideal for modern deployment scenarios (GitHub Actions, Docker, Azure Pipelines, etc.).
- ⚙️ **Minimal Setup**: Just use the static `ConnectionString.GetConnectionString(...)` helper.

---

## 🧠 Ideal For

- Developers aiming for **secure database handling**
- Teams implementing **Clean Architecture**
- Applications using **Entity Framework Core**
- Environments with **multiple DB configurations** (Dev, QA, Prod)

---

## 📄 Documentation

Full guide included in the repository:

📎 [`DynamicDatabaseConnection.docx`](./Docs/DynamicDatabaseConnection.docx)
