Database for Restaurant Management System
This project focuses on the creation and management of a Restaurant Database designed to handle various restaurant operations, such as managing orders, menu items, and customer information. The database is connected to a C# application through Oracle Database to enable seamless interaction between the application and the data storage system.

Features
Database Design: The database is structured to support core restaurant functions, including menus, orders, customers, and staff management.
Oracle Database: The database is built and managed using Oracle as the relational database management system (RDBMS).
C# Integration: A C# application is developed to interact with the Oracle database, enabling data manipulation and retrieval through a simple and efficient interface.
SQL Queries: Various SQL queries are written to perform necessary operations such as inserting, updating, deleting, and retrieving data.
ERD (Entity-Relationship Diagram): An ERD has been created to visualize the database structure and relationships between the entities involved (e.g., Menu, Orders, Customers, Employees).
Technologies Used
Oracle Database: Used to store and manage the restaurant's data.
C#: The application is developed using C# to interact with the database, providing a simple interface for managing data and performing operations.
SQL: SQL queries are written to handle database operations, such as creating tables, inserting data, and performing complex searches and updates.
Visual Studio: Visual Studio is used as the integrated development environment (IDE) to build the C# application and manage the connection to the Oracle database.
Database Functionality
Key Components:
Menus:
The system allows the addition and modification of menu items. Each item contains information such as the item name, price, and category (e.g., appetizers, main courses, drinks).
Orders:
Customers can place orders, which are stored in the database with details like the order ID, customer ID, item IDs, quantity, and total price.
Customers:
The database keeps track of customer information, including personal details, contact information, and order history.
Staff:
The system stores information about staff members, including their roles, names, and contact details.
Operations:
Inserting Data: The C# application allows inserting new data into the database, such as adding new menu items, processing customer orders, or adding new customers.
Retrieving Data: SQL queries are used to fetch data for displaying on the application interface, such as listing all menu items or viewing a customer's order history.
Updating Data: Changes to the database (such as updating prices or order status) are done through C#-generated SQL queries.
Deleting Data: Unnecessary data, such as canceled orders or outdated menu items, can be removed using SQL queries.
ERD (Entity-Relationship Diagram)
An Entity-Relationship Diagram (ERD) was created to represent the database structure visually. The ERD shows how different entities (e.g., Menu, Orders, Customers, Staff) are related to each other. For example, Customers can place multiple Orders, and each Order can contain multiple Menu Items.

The ERD helps in understanding the relationships between various parts of the restaurant system and ensures the database design is robust and efficient.

Validation and Testing
Query Testing: After implementing the database and application, various SQL queries were run to ensure that all operations (insert, update, delete, retrieve) work as expected.
Functionality Testing: The system was tested to verify that users can interact with the application, make orders, update data, and fetch information correctly.
The testing phase helped confirm the integrity and reliability of the database and the connection between the C# application and Oracle database.
