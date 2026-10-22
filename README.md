# Hi, I'm Abdelrahman
 
Backend engineer building secure, well-tested REST APIs with Java and Spring Boot.

---

## Featured Project

### [Library Management System](https://github.com/Abzanatii/library-management-system)

A Spring Boot backend for running a library: collection and physical copies, borrowing and returning, fines, and a reservation queue. Built as a modular monolith with a package-by-feature structure.

[Source code](https://github.com/Abzanatii/library-management-system) · [Postman collection](https://github.com/Abzanatii/library-management-system/tree/main/postman)

- Stateless JWT authentication with role-based access (ADMIN, LIBRARIAN, CUSTOMER) via Spring Security
- Reservation queue with a 48-hour hold and automatic hand-off to the next customer, driven by domain events
- Optimistic locking so two customers can never borrow the same copy at once
- PostgreSQL with Flyway migrations, and database constraints as a safety net for key business rules
- Unit tests with JUnit 5, Mockito and a fixed `Clock` for exact due-date and fine calculations
- Swagger UI, a full Postman collection, and consistent error responses across the API

**Stack:** Java 21 · Spring Boot · Spring Data JPA · PostgreSQL · Flyway · JWT · Maven

---

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
 
**Also working with:** Flyway · JWT · Mockito · Git · OpenAPI/Swagger · Postman · MapStruct · Lombok
