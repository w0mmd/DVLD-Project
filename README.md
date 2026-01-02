DVLD – Driving & Vehicle Licensing Department System

DVLD is a real-world desktop application that simulates the core operations of a Driving & Vehicle Licensing Department. The project is designed to reflect actual government workflows related to driver licensing, applications, driving tests, and license lifecycle management.

This system was developed as a practical, production-style project, focusing on implementing real business rules and workflows rather than simple CRUD operations.

Key Features

People & Drivers Management
Manage citizens and drivers data, and link people to drivers and their licenses.

License Applications
Support for Local Driving License Applications, International Driving License Applications, license renewal, replacement (lost or damaged), and release of detained licenses.

Driving Tests Workflow
Includes Vision Test, Written Test, and Street Test, with enforced test order based on real regulations and application status.

Licenses Management
Issue local and international licenses, view full license history, and activate or deactivate licenses.

Detained Licenses
Detain and release licenses, and track detention records and license status.

Users & Security
Secure login system with user roles and permissions.

Architecture

The project follows a clean 3-Tier Architecture:

Presentation Layer
Windows Forms (WinForms) for the user interface.

Business Logic Layer (BLL)
Implements real business rules, validations, and workflow enforcement.

Data Access Layer (DAL)
SQL Server integration using ADO.NET with parameterized queries and structured data handling.

Technologies Used

C# (.NET Framework)

Windows Forms (WinForms)

SQL Server

ADO.NET

Object-Oriented Programming (OOP)

Inheritance and Composition

Project Purpose

This project was built to simulate a real governmental licensing system and to demonstrate strong understanding of OOP principles, multi-layer application design, real business logic implementation, and database-driven desktop development.

All workflows are implemented based on realistic DVLD rules. The project is structured for scalability and maintainability and is intended for learning, demonstration, and portfolio purposes.

