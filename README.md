# CR-Bank System 
> A simple Bank System application that allows clients, employees, and admins to manage banking operations.
> > <img align="right" alt="Route Logo" width="200" src="https://github.com/user-attachments/assets/c72325df-b2dd-4ca4-839a-d7969f82ed22">
**Team members:**
- [Youssef Sami](https://github.com/Youssef-Sami-1)
- [Yasmin Mohamed](https://github.com/yasmiine-mohamed)
- [Ahmed ElSayed](https://github.com/ahmed-elsayed2)
- [kamel Sabry](https://github.com/kamel5102003)
- Yehia Sami
---
## Introduction
> This system is divided into three modules: **Client Module**, **Employee Module**, and **Admin Module**. Each module provides specific functionalities for users to interact with the system.
---
### Phase 1: Core Implementation
In **Phase 1**, we focus on implementing the core classes and functionalities for the **Client**, **Employee**, and **Admin** modules. These classes serve as the foundation for the system, with a focus on data encapsulation, validation, and basic operations.

### Features Implemented in Phase 1

### 1. Client Class Attributes:
- int id
- string name
- string password
- double balance

**Methods:**
- setName: Validates and sets the client's name (must be alphabetic, 5-20 characters).
- setPassword: Validates and sets the client's password (must be 8-20 characters).
- deposit: Allows the client to deposit money into their account.
- withdraw: Allows the client to withdraw money from their account.
- transferTo: Allows the client to transfer money to another client.
- checkBalance: Displays the client's current balance.
- display: Displays the client's information.

### 2. Employee Class Attributes:
- int id
- string name
- string password
- double salary

**Methods:**

- setName: Validates and sets the employee's name (must be alphabetic, 5-20 characters).
- setPassword: Validates and sets the employee's password (must be 8-20 characters).
- display: Displays the employee's information.

### 3. Admin Class Attributes:

- Inherits from the Employee class.

**Methods:**

- Inherits all methods from the Employee class.

### 4. Validation Class:

**Contains static methods for validating inputs:**

- validateName: Ensures names are alphabetic and within the required length.

- validatePassword: Ensures passwords are within the required length.

- validateBalance: Ensures the balance meets the minimum requirement (1500 for clients).

- validateSalary: Ensures the salary meets the minimum requirement (5000 for employees and admins).
---
## Acknowledgments
- This project is part of a course and is for educational purposes.
