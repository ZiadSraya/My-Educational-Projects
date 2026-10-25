
# DVLD — Driving License Management System

A comprehensive desktop application for managing driving license services, built as a practical software engineering project using C#, Windows Forms, SQL Server, and ADO.NET.

## Overview

The Driving License Management System (DVLD) is a database-driven application designed to organize the workflows involved in managing people, users, driving license applications, tests, drivers, and issued licenses.

This project is part of my programming learning journey and focuses on applying object-oriented programming, database design, layered architecture, and application development to a large, multi-module system.

## Main Features

### 1. People Management
- Add, update, search, and manage people's information.
- Manage country information.
- Handle person images.
- Reusable person information and card controls.

### 2. User Management and Authentication
- Manage application users.
- Login functionality.
- Account settings and password changes.
- Separate user and person information.

### 3. Application Configuration
- Manage application types.
- Manage driving test types.
- Configure application-related information.

### 4. Local Driving License Applications
- Create local driving license applications.
- Manage application information and status.
- Associate applications with people and license classes.
- List and review local driving license applications.

### 5. Test Scheduling and Results
- Schedule driving tests.
- Manage test appointments.
- Record test results.
- Handle failed tests and retake applications.

### 6. Driving License Management
- Issue a driving license for the first time.
- Renew existing licenses.
- Replace lost or damaged licenses.
- View driver and license information.
- Review a person's license history.

### 7. International Driving Licenses
- Create international driving license applications.
- Manage international license application records.
- List and review international applications.

### 8. Detained Licenses
- Detain driving licenses.
- Release detained licenses.
- Manage detained license records.

## Technical Stack

- **Language:** C#
- **User Interface:** Windows Forms
- **Database:** Microsoft SQL Server
- **Database Connectivity:** ADO.NET
- **Programming Paradigm:** Object-Oriented Programming
- **Architecture:** Layered architecture with Business Logic and Data Access layers
- **Database Access:** SQL queries, commands, and stored procedures where applicable

## Architecture and Design

The project demonstrates separation of responsibilities between application components.

### Presentation Layer
Responsible for forms, user interactions, reusable controls, validation feedback, and displaying information.

### Business Logic Layer
Responsible for application rules, business operations, and coordinating workflows.

### Data Access Layer
Responsible for communicating with SQL Server and executing database operations.

### Database Layer
Stores and relates information about people, users, applications, tests, drivers, licenses, and related records.

This separation helps keep user interface code, business rules, and database operations organized and easier to maintain.

## Database Design

The database includes entities and relationships covering:

- People and countries
- Users
- Applications and application types
- Local driving license applications
- License classes
- Test types, appointments, and results
- Drivers and licenses
- License renewal and replacement workflows
- Detained licenses and release operations
- International license applications

The database structure supports the relationships and workflows required by the application's main modules.

## Concepts Practiced

Through this project, I studied and applied:

- Object-Oriented Programming in a larger application
- Encapsulation and separation of responsibilities
- Composition and reusable UI controls
- Events, delegates, and communication between forms
- Three-tier application design
- Business Logic Layer and Data Access Layer
- ADO.NET database connectivity
- Relational database design and entity relationships
- CRUD operations
- Authentication and account management
- Business rules and input validation
- Multi-step application workflows
- Database-driven desktop application development

## Getting Started

The following steps describe the general setup process. Exact requirements may depend on the version of the source code included in this repository.

### Prerequisites

- Windows
- Visual Studio with the required C# and Windows Forms components
- Microsoft SQL Server
- SQL Server Management Studio (SSMS), or another suitable SQL Server client
- A compatible .NET Framework version for the project

### Setup

1. Clone or download this repository.
2. Locate the Visual Studio solution (`.sln`) or project file (`.csproj`).
3. Open the solution in Visual Studio.
4. Locate the provided database backup or SQL database scripts, if included.
5. Restore or create the database in SQL Server.
6. Review the application's database connection string and update it for your SQL Server instance.
7. Build the solution and run the application.

**Note:** Database restoration, connection string configuration, and framework requirements depend on the actual project files included in the repository.

## Project Structure

The repository may contain the following components, depending on how the source files are organized:

```text
DVLD/
├── README.md
├── Database/
│   └── Database backup or scripts
├── Presentation/
│   └── Windows Forms and reusable controls
├── Business/
│   └── Business logic and application workflows
└── DataAccess/
    └── SQL Server access and database operations
```

This is an illustrative structure, not a claim about the exact directory layout of the uploaded source code.

## Learning Objectives

The primary objective of this project is to move beyond isolated programming exercises and understand how multiple components work together in a substantial software application.

The project provides practical exposure to:

- Translating requirements into application features.
- Designing and navigating a relational database.
- Connecting desktop interfaces to a database.
- Organizing code into separate layers.
- Implementing workflows that involve multiple entities.
- Understanding and maintaining a larger codebase.

## Project Status

Educational project completed as part of a structured programming roadmap.

The repository should be evaluated according to the source code, database files, documentation, and any modifications actually included.

## Acknowledgements

This project was studied and developed as part of the programming roadmap and educational materials provided by **Programming Advices / Abu-Hadhoud**.

The original educational materials and any third-party assets remain subject to their respective ownership and licensing terms.

## Disclaimer

This repository is intended for educational purposes. It does not represent a production deployment or an officially certified driving license management system.

Features, architecture descriptions, and setup instructions should be verified against the actual files included in this repository.
