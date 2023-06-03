# BWorks
## Introduction

The BWorks project aims to create a platform for bicycle enthusiasts, where they can donate or purchase bicycles. This platform provides a user-friendly interface and leverages the power of SQLAlchemy, a Python library for working with databases, along with SQL Server Management Studio (SSMS) as the database management system.

The core entities in the BWorks project are Users, Bicycles, and Transactions. The Users entity represents individuals who interact with the platform. It stores important information about users, including their name, email, address, username, and password. Users can have a collection of bicycles associated with them, forming a one-to-many relationship.

The Bicycles entity captures details about each bicycle available for donation or purchase. It stores information such as the brand, model, color, condition, and availability of the bicycle. Each bicycle is associated with a specific user, allowing users to track their own bicycles and manage them effectively. The relationship between Users and Bicycles is established through a foreign key constraint.

Transactions play a crucial role in the BWorks project as they represent the interaction between users and bicycles. Each transaction involves a specific bicycle and a user. It contains information about the transaction date and whether the transaction is a donation or a purchase. The transaction entity enables the platform to track the history of bicycle movements and facilitate smooth operations.The BWorks project makes use of SQLAlchemy's ORM (Object-Relational Mapping) to streamline database operations. With SQLAlchemy, developers can interact with the database using Python objects and classes, eliminating the need for manual composition of intricate SQL queries. The platform relies on SQL Server Management Studio (SSMS) as the database management system, ensuring a reliable and scalable solution.

With the BWorks project, users can easily navigate the platform, donate their bicycles to others, or purchase bicycles from available listings. The intuitive user interface allows users to search for specific bicycles based on brand, model, or other criteria. Users can also view the details of a bicycle, including its condition and availability status.

The BWorks project enhances the accessibility of bicycles and fosters a culture of sharing and community involvement. Through the integration of SQLAlchemy with Python and SSMS, the project offers a reliable and efficient solution for managing bicycle donation and purchase transactions.

## Block Diagram


![image](https://github.com/KNagaPrasad/BWorks/assets/129809773/c7247ce7-2e8f-455b-8af3-575fb940fbd5)

User Interface: The user interacts with the BWorks project through a user interface, which provides a visually appealing and intuitive platform for users to donate or purchase bicycles. The interface allows users to input their preferences, search for bicycles, and perform various actions.

User Actions: Users perform actions such as donating a bicycle, purchasing a bicycle, searching for bicycles, and managing their own bicycle listings. These actions are initiated by the user through the user interface.

Backend Processing: Once the user performs an action, the backend processes the request and performs the necessary operations. This includes handling the logic, validating user input, and coordinating the interaction between different components.

Database Operations: The backend interacts with the database management system, which in this case is SQL Server Management Studio (SSMS). The database operations involve inserting, updating, or retrieving data from the database tables. These operations are performed using SQLAlchemy, a Python library for working with databases.


