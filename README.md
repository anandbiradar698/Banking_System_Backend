 Banking System – Spring Boot Backend
A backend banking system built using Spring Boot, Spring Data JPA, MySQL, and RESTful APIs.
Originally implemented in Core Java and later refactored to Spring Boot following industry-standard backend architecture and best practices.

🚀 Features
Create and manage users
Create bank accounts
Deposit and withdraw money
Transfer money between accounts (atomic & transactional)
Check account balance
Implemented caching to optimize read-heavy operations
🛠️ Tech Stack
Java 17
Spring Boot
Spring Data JPA (Hibernate)
MySQL
Spring Cache (In-Memory Caching)
REST APIs
Maven
Postman (API Testing)
🧩 Project Architecture
The project follows a layered architecture:

Controller Layer
Handles REST API requests and responses.

Service Layer
Contains business logic such as deposit, withdraw, transfer, and caching.

Repository Layer
Uses Spring Data JPA to interact with the database.

Model Layer
JPA entities representing database tables.

🔁 Key Backend Concepts Implemented
💰 Transaction Management
Implemented using @Transactional
Ensures atomic operations for fund transfers
Prevents partial updates and maintains data consistency
⚡ Caching Strategy
Implemented using Spring Cache (@Cacheable, @CachePut, @CacheEvict)
Optimizes frequently accessed data (account balance)
Reduces redundant database calls
Maintains cache consistency by updating/evicting cache on data modification
🧠 Service Design
Centralized business logic in AccountService
Ensures single source of truth for account operations
Prevents cache inconsistency and duplicate logic
