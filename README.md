🚀 HRM System Backend – ASP.NET Web API & SQL Server

This backend is developed using ASP.NET Web API with ADO.NET and Microsoft SQL Server, designed to power a complete Human Resource Management (HRM) System.

It provides secure and efficient RESTful APIs to manage employee records, organizational structure, and master data required for HR operations.

🔧 Technologies Used

ASP.NET Web API

C#

ADO.NET

Microsoft SQL Server

RESTful Architecture

📦 Core Features
👤 Employee Management

Create new employees

Update employee details

Delete employees

View all employees

Retrieve single employee with full relational data for editing

🏢 Organizational Master Data

Divisions

Departments

Department-based Locations

Designations

Education Levels

Hometowns

🔗 Smart Relational Handling

All employee data is stored using foreign key relationships

APIs return both ID and display values enabling frontend dropdown auto-selection and seamless editing experience

⚡ Optimized Data Access Layer

Centralized ADO.NET data access layer

Parameterized queries to prevent SQL Injection

Clean and maintainable repository structure

🗄️ Database Design

Fully normalized relational schema

Foreign key constraints for data integrity

Department → Location dependency handled via APIs

All dropdown datasets exposed as independent APIs
