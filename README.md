# Employee Management System – ASP.NET Core Web API

## Overview

Employee Management System – ASP.NET Core Web API is a RESTful API developed using ASP.NET Core Web API, C#, Entity Framework Core, and SQL Server. The application provides CRUD (Create, Read, Update, Delete) operations for managing employee records through HTTP endpoints.

This project demonstrates REST API development, Entity Framework Core Code First approach, database integration, model validation, and API testing.

---

## Features

- Create employee records
- Retrieve all employees
- Retrieve employee details by ID
- Update employee information
- Delete employee records
- RESTful API architecture
- Entity Framework Core Code First approach
- EF Core Migrations
- SQL Server database integration
- JSON request and response
- Model validation

---

## Technologies Used

### Backend

- ASP.NET Core Web API
- C#
- Entity Framework Core

### Database

- Microsoft SQL Server

### API

- REST API
- JSON

### Development Tools

- Visual Studio 2022
- SQL Server Management Studio (SSMS)

---

## Project Architecture

```
Client
   |
HTTP Request
   |
ASP.NET Core Web API
   |
Controller
   |
Entity Framework Core
   |
SQL Server Database
```

---

## Project Structure

```
EmployeeAPI

│
├── Controllers
│   └── EmployeeController.cs
│
├── Models
│   └── Employee.cs
│
├── Data
│   └── EmployeeDbContext.cs
│
├── Migrations
│
├── appsettings.json
│
└── Program.cs
```

---

## Database Details

Database Name

```
EmployeeManagementDB
```

Table Name

```
Employee
```

Employee Table

| Column | Data Type |
|---------|-----------|
| Id | int |
| Name | varchar |
| Designation | varchar |
| Salary | decimal |

---

## API Endpoints

### Get All Employees

```
GET /api/Employee
```

---

### Get Employee By ID

```
GET /api/Employee/{id}
```

---

### Create Employee

```
POST /api/Employee
```

Sample JSON

```json
{
  "name": "Lakshmi",
  "designation": "Software Developer",
  "salary": 35000
}
```

---

### Update Employee

```
PUT /api/Employee/{id}
```

---

### Delete Employee

```
DELETE /api/Employee/{id}
```

---

## Entity Framework Core

This project uses the Code First approach with Entity Framework Core.

Migration Commands

```bash
Add-Migration InitialCreate

Update-Database
```

---

## How to Run the Project

1. Clone the repository.

2. Open the solution using Visual Studio 2022.

3. Update the SQL Server connection string inside:

```
appsettings.json
```

4. Run EF Core migrations.

5. Build the project.

6. Run the application.

7. Open the API using:

```
https://localhost:7242/api/Employee
```



## Future Enhancements

- Authentication and Authorization using JWT
- Search employees
- Pagination
- Sorting
- Swagger API documentation
- Logging
- Unit Testing

---

## Author

**Lakshmi Priya**

GitHub: https://github.com/lakshmiraj070-arch

---

## License

This project is developed for learning and portfolio purposes.
