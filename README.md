# Spring Boot Notes

Structured lecture notes and practical reference material for backend development with Spring, Spring Boot, JPA, and Spring Security.

## What This Repository Contains

- A step-by-step path from web fundamentals to production-style Spring Boot API design.
- Notes focused on practical implementation patterns, not just theory.
- Topic progression aligned with real project building: API basics -> persistence -> validation -> pagination -> product module -> security.

## Complete Index

| # | Topic | Focus |
|---|---|---|
| 1 | [Basics of Web Development and Internet](1.%20BasicsOfWebDev%26%26Internet.md) | Client-server model, APIs, REST, HTTP/HTTPS, status codes, URI/resources |
| 2 | [Spring Framework](2.%20SpringFramework.md) | IoC, DI, XML config, bean wiring, coupling concepts |
| 3 | [Spring Annotations](3.%20SpringAnnotations.md) | `@Component`, `@Autowired`, `@Qualifier`, `@Value`, component scanning |
| 4 | [Spring Boot 101](4.%20SpringBoot101.md) | Boot setup, starters, first APIs, project structure, `application.properties` |
| 5 | [Databases and Persistence](5.%20Databases%26Persistence.md) | DBMS basics, relational concepts, SQL categories, ORM overview |
| 6 | [JPA](6.%20JPA.md) | Entities, repositories, layered architecture, H2, Spring Data JPA |
| 7 | [Lombok](7.%20LOMBOK.md) | Boilerplate reduction, core annotations, setup and troubleshooting |
| 8 | [Validations and Custom Exceptions](8.%20Validations%26CustomExceptionsInSpringBoot.md) | Bean validation, `@Valid`, global exception handling, API error responses |
| 9 | [Pagination and Sorting](9.%20Pagination%26Sorting.md) | Pageable APIs, DTO pattern, ModelMapper, response metadata |
| 10 | [JPA Relationships](10.%20WorkingWithMultipleEntitiesAndRelationshipsWithJPA.md) | One-to-one, one-to-many, many-to-many, cascade/fetch, JSON recursion concerns |
| 11 | [Managing Products in E-commerce App](11.%20ManagingProductsInOurEcommerceApplication.md) | Product CRUD, search, image upload, service/repository/API contract |
| 12 | [Spring Security](12.%20SpringSecurity.md) | Authentication/authorization, password hashing, JWT flow, secure API setup |

## Suggested Learning Path

Follow the notes in numeric order for the smoothest progression:

1. Web and API foundations
2. Spring Core and annotation-based configuration
3. Spring Boot app building
4. Persistence and JPA
5. Production API patterns (validation, exceptions, pagination)
6. Multi-entity data modeling
7. Full e-commerce module implementation
8. Security and JWT-based authentication

## Quick Navigation

- Fundamentals: [1. Basics](1.%20BasicsOfWebDev%26%26Internet.md), [2. Spring Framework](2.%20SpringFramework.md), [3. Annotations](3.%20SpringAnnotations.md), [4. Spring Boot 101](4.%20SpringBoot101.md)
- Data Layer: [5. Databases](5.%20Databases%26Persistence.md), [6. JPA](6.%20JPA.md), [10. JPA Relationships](10.%20WorkingWithMultipleEntitiesAndRelationshipsWithJPA.md)
- API Quality: [7. Lombok](7.%20LOMBOK.md), [8. Validations and Exceptions](8.%20Validations%26CustomExceptionsInSpringBoot.md), [9. Pagination and Sorting](9.%20Pagination%26Sorting.md)
- Applied Module + Security: [11. Product Module](11.%20ManagingProductsInOurEcommerceApplication.md), [12. Spring Security](12.%20SpringSecurity.md)

## Repository Notes

- `TEMP.md` is currently empty and can be used as scratch space.
- `pictures/` is currently empty and available for future diagrams/screenshots.

## Goal

Use this repository as a compact backend handbook while building real Spring Boot projects. Each note is designed to be revision-friendly and implementation-focused.
