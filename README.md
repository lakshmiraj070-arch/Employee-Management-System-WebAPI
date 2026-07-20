# Employee Management System MVC

## Overview

Employee Management System MVC is an ASP.NET Core MVC application developed to manage employee records efficiently. The application follows the MVC (Model-View-Controller) architecture and performs CRUD operations using Entity Framework Core with SQL Server.

This project demonstrates the implementation of MVC concepts, database connectivity, form validation, and Razor Views.

## Features

* View all employee records
* Add new employee details
* Edit existing employee information
* Delete employee records
* Form validation using Data Annotations
* Entity Framework Core database integration
* SQL Server database connectivity
* Responsive user interface using HTML and CSS

## Technologies Used

### Backend

* ASP.NET Core MVC
* C#
* Entity Framework Core

### Database

* Microsoft SQL Server

### Frontend

* Razor Views (.cshtml)
* HTML5
* CSS3
* Bootstrap

### Development Tools

* Visual Studio 2022
* SQL Server / SQL Server Management Studio

## Application Architecture

The project follows the MVC architecture:

```
User
 |
 v
View (Razor Pages)
 |
 v
Controller
 |
 v
Model
 |
 v
Entity Framework Core
 |
 v
SQL Server Database
```

## Project Structure

```
EmployeeManagementSystemMVC

│
├── Controllers
│   ├── HomeController.cs
│   └── EmployeesController.cs
│
├── Models
│   ├── Employee.cs
│   ├── EmployeeManagementDBContext.cs
│   └── ErrorViewModel.cs
│
├── Views
│   ├── Home
│   ├── Employees
│   │   ├── Index.cshtml
│   │   ├── Create.cshtml
│   │   ├── Edit.cshtml
│   │   ├── Details.cshtml
│   │   └── Delete.cshtml
│   │
│   └── Shared
│
├── wwwroot
│   └── css
│
├── appsettings.json
└── Program.cs
```

## Database Details

Database Name:

```
EmployeeManagementDB
```

Table Name:

```
Employee
```

Employee Table Columns:

| Column      | Data Type |
| ----------- | --------- |
| Id          | int       |
| Name        | varchar   |
| Designation | varchar   |
| Salary      | decimal   |

## CRUD Operations

### Create

Allows users to add new employee records through a form with validation.

### Read

Displays all employee records from SQL Server.

### Update

Allows users to edit and update existing employee information.

### Delete

Allows users to remove employee records from the database.

## Validation

Implemented using ASP.NET Core Data Annotations:

* Required field validation
* String length validation
* Salary range validation

## How to Run the Project

1. Clone the repository

2. Open the project using Visual Studio 2022

3. Update the SQL Server connection string in:

```
appsettings.json
```

4. Build the solution

5. Run the application

6. Navigate to:

```
https://localhost:7073/Employees
```



## Future Enhancements

* User authentication and authorization
* Search and filter employees
* Pagination
* Export employee details to Excel
* Improved responsive design

## Author

Lakshmi Priya

## License

This project is created for learning and portfolio purposes.
