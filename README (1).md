# 📚 CourseApp — Course Registration System

A web application for managing and applying to in-class training programs, built with ASP.NET Core MVC.

---

## 🛠️ Tech Stack

![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-8.0-blue?style=flat-square&logo=dotnet)
![EF Core](https://img.shields.io/badge/Entity%20Framework%20Core-8.0-purple?style=flat-square)
![SQL Server](https://img.shields.io/badge/SQL%20Server-2022-red?style=flat-square&logo=microsoftsqlserver)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-blueviolet?style=flat-square&logo=bootstrap)
![C#](https://img.shields.io/badge/C%23-12.0-green?style=flat-square&logo=csharp)

---

## 📌 About

CourseApp is a full-stack course registration platform that allows users to browse available in-class training programs and submit applications. Administrators can manage courses, view applicants, and track enrollment status through a dedicated admin panel.

---

## ✨ Features

- [ ] Course listing with category filtering
- [ ] Course detail page
- [ ] User registration & login (ASP.NET Identity)
- [ ] Course application form
- [ ] Application status tracking
- [ ] Admin panel — course CRUD operations
- [ ] Admin panel — applicant management
- [ ] Responsive UI with Bootstrap 5

---

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/sql-server) or SQL Server Express

### Run Locally

```bash
# Clone the repository
git clone https://github.com/selinyalcn/CourseApp.git
cd CourseApp

# Restore dependencies
dotnet restore

# Apply database migrations
dotnet ef database update

# Run the application
dotnet run
```

App will be available at `https://localhost:5001`

---

## 🏗️ Project Structure

```
CourseApp/
├── Controllers/        # MVC Controllers
├── Models/             # Domain models & ViewModels
├── Views/              # Razor Views
├── Data/               # EF Core DbContext & Migrations
├── wwwroot/            # Static files (CSS, JS, images)
└── Areas/
    └── Admin/          # Admin panel area
```

---

## 📸 Screenshots

> Will be added as the project progresses.

---

## 🗺️ Roadmap

- [x] Project setup with ASP.NET Core MVC template
- [ ] Database design & Entity Framework Core integration
- [ ] Course listing & detail pages
- [ ] User authentication (ASP.NET Identity)
- [ ] Application form & submission flow
- [ ] Admin panel
- [ ] Deployment

---

## 📄 License

MIT
