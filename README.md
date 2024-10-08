# Library Management System

This project is a **Library Management System** developed using **C# .NET 8** following the **3-Tier Architecture** pattern. It is designed to showcase my skills in thinking big to plan a project that has different components that interact and integrate together following a systimatic steps to plan the project following SOLID Principles, Design Patterns and coding best prctices to ensure the Software Quality Criteria and create a well-structured system from initial requirements gathering to implementation.

## Features
- **Manage Books**: Add, update, remove, and search for books in the library system.
- **Manage Users**: Create and manage library members, including borrowing and returning books.
- **Loan Management**: Handle the borrowing and returning process, including tracking due dates and overdue books.
- **Reports**: Generate reports on book availability, user activity, and loan statuses.

## Project Architecture
- **3-Tier Architecture**: The application is divided into three layers:
  - **Presentation Layer**: Handles the user interface and communication with the business logic.
  - **Business Logic Layer**: Contains the core functionality and rules for managing the library.
  - **Data Access Layer**: Interacts with the database using **ADO.NET**.
  - **Entity/Domain Model**: Maps the data between the database and the business objects.
  
- **SOLID Principles**: Applied throughout the project to ensure that the code is maintainable, flexible, and scalable.
  
- **Design Patterns**: Implements design patterns such as Repository Pattern and Dependency Injection to separate concerns and improve code quality.

## Database Design
- **Relational Schema**: The database schema is carefully designed using **Normalization** principles to avoid redundancy and ensure data integrity.
- **Data Access**: **ADO.NET** is used to connect the application to the database and perform CRUD operations efficiently.

## Technologies Used
- **C# .NET 8**
- **ADO.NET** for database access
- **SQL Server** for database design
- **3-Tier Architecture** as an archetectural pattern
- **Design Patterns** (e.g., Repository, Dependency Injection)

## Goals
This project demonstrates my ability to:
- **Plan and Design**: Translate business requirements into a structured system.
- **Architect a Scalable System**: Using 3-Tier Architecture for separation of concerns.
- **Implement Design Patterns**: Apply best practices in software design for reusability and maintainability.
- **Implement SOLID Principles**: to reduce dependencies so that i can change one area of the software without impacting others. They make it easier to understand, maintain, and extend designs.

## Future Enhancements
- **Authentication and Authorization**: Add user roles and permissions.
- **Multi-Branch Support**: Expand the system to handle multiple library branches.
- **Automated Testing**: Implement unit and integration tests for different components.

## Getting Started
To run this project locally:
1. Clone the repository:
    ```bash
    git clone https://github.com/Algorithm-Archetict/My-Library-Managment-System.git
    ```
2. Build the solution in Visual Studio.
3. Set up the database using the SQL scripts. (i will provide them later)
4. Run the application and start managing your library.

---

Feel free to explore the repository and provide feedback!
