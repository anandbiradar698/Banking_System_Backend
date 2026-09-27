# 🏦 Banking System – Spring Boot Backend

A backend banking system built using **Spring Boot, Spring Data JPA, MySQL, and REST APIs**.

The project provides REST APIs for managing users, bank accounts, deposits, withdrawals, money transfers, and account balances. It also demonstrates transaction management, caching, and a layered backend architecture.

---

## 🚀 Features

- Create and manage users
- Create bank accounts
- Deposit money
- Withdraw money
- Transfer money between accounts
- Check account balance
- Transaction management using `@Transactional`
- Spring Cache for frequently accessed data
- RESTful APIs
- Layered architecture
- MySQL database integration
- JPA/Hibernate for database operations

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Spring Cache**
- **REST API**
- **Maven**
- **Postman**

---

## 🏗️ Project Architecture

The project follows a layered architecture:

```text
Controller Layer
       ↓
Service Layer
       ↓
Repository Layer
       ↓
Model / Entity Layer
       ↓
     MySQL
