# EmployeeAPI

## Overview

EmployeeAPI is a RESTful ASP.NET Core Web API developed for an Employee Management System. It provides CRUD (Create, Read, Update, Delete) operations for managing employee records and uses Entity Framework Core with SQL Server for data storage.

This API is designed to be consumed by a React.js frontend, enabling a complete Full Stack Employee Management System.

---

## Features

- Add a new employee
- View all employees
- View employee by ID
- Update employee details
- Delete employee
- RESTful API architecture
- Entity Framework Core integration
- SQL Server database connectivity

---

## Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server
- REST API
- Visual Studio 2022

---

## Project Structure

```
EmployeeAPI
│
├── Controllers
├── Models
├── Data
├── Migrations
├── Properties
├── Program.cs
├── appsettings.json
└── EmployeeAPI.csproj
```

---

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/Employee | Get all employees |
| GET | /api/Employee/{id} | Get employee by ID |
| POST | /api/Employee | Add a new employee |
| PUT | /api/Employee/{id} | Update employee |
| DELETE | /api/Employee/{id} | Delete employee |

---

## Database

The project uses SQL Server with Entity Framework Core.

Example Employee model:

- Id
- Name
- Designation
- Salary

---

## Future Enhancements

- Authentication & Authorization using JWT
- Pagination
- Search and Filtering
- Logging
- Exception Handling Middleware
- Swagger Documentation

---

## Author

**Lakshmi Priya**

GitHub: https://github.com/lakshmiraj070-arch
