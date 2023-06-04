# BWorks
## Introduction

The BWorks project aims to create a platform for bicycle enthusiasts, where they can donate or purchase bicycles. This platform provides a user-friendly interface and leverages the power of SQLAlchemy, a  Python library for working with databases, along with SQL Server Management Studio (SSMS) as the database management system.

The core entities of the BWorks project are Users, Bicycles, and Transactions. Users represent individuals who interact with the platform, storing essential information such as their name, email, address, username, and password. Users can have multiple associated bicycles, creating a one-to-many relationship.

The Bicycles entity has data about each bicycle that is available for purchase or gift, including the brand, model, color, availability, and condition. Bicycles are linked to certain users, making it possible to track and manage them efficiently. A foreign key constraint is used to build the link between Users and Bicycles.

Transactions are vital in the BWorks project as they capture user-bicycle interactions.Every transaction includes a bicycle, a user, the transaction date, and the type of transaction (donation or purchase). This organization maintains a history of bicycle movements and guarantees smooth operations.

SQLAlchemy's ORM is used by the BWorks project to streamline database operations. Instead than utilizing intricate SQL queries, SQLAlchemy allows developers to connect with the database using Python objects and classes. The database management system for the project is SQL Server Management Studio (SSMS), which offers a dependable and scalable solution.

With the BWorks project, users can easily navigate the platform, donate their bicycles to others, or purchase bicycles from available listings. The intuitive user interface allows users to search for specific bicycles based on brand, model, or other criteria. Users can also view the details of a bicycle, including its condition and availability status.

The BWorks project enhances the accessibility of bicycles and fosters a culture of sharing and community involvement. Through the integration of SQLAlchemy with Python and SSMS, the project offers a reliable and efficient solution for managing bicycle donation and purchase transactions.

## Block Diagram


![image](https://github.com/KNagaPrasad/BWorks/assets/129809773/c7247ce7-2e8f-455b-8af3-575fb940fbd5)

User Interface: The user interacts with the BWorks project through a user interface, which provides a visually appealing and intuitive platform for users to donate or purchase bicycles. The interface allows users to input their preferences, search for bicycles, and perform various actions.

User Actions: Users perform actions such as donating a bicycle, purchasing a bicycle, searching for bicycles, and managing their own bicycle listings. These actions are initiated by the user through the user interface.

Backend Processing: Once the user performs an action, the backend processes the request and performs the necessary operations. This includes handling the logic, validating user input, and coordinating the interaction between different components.

Database Operations: The backend interacts with the database management system, which in this case is SQL Server Management Studio (SSMS). The database operations involve inserting, updating, or retrieving data from the database tables. These operations are performed using SQLAlchemy, a Python library for working with databases.


