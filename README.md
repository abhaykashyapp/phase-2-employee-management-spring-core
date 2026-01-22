# Employee Management – Spring Core (Phase 2)

A Java console application built to understand **Spring Core fundamentals**, including **Inversion of Control (IoC)**, **Dependency Injection (DI)**, **bean lifecycle**, and **Spring AOP** using annotation-based configuration.

This phase focuses on learning how Spring manages objects internally before moving to Spring Boot, databases, or web development.

---

## Phase 2 Objectives

- Understand why Spring exists and the problems it solves
- Learn Inversion of Control (IoC) and Dependency Injection (DI)
- Convert a core Java application into a Spring-managed application
- Understand Spring bean lifecycle and scopes
- Apply Spring AOP for cross-cutting concerns (logging)
- Keep business logic clean and framework-independent

---

## Features Implemented

- Spring Core configuration using Java-based config
- Annotation-driven component scanning
- Spring-managed `Service` and `Repository` beans
- Dependency Injection using `@Autowired`
- Application bootstrapped via `ApplicationContext`
- Logging implemented using **Spring AOP**
  - `@Aspect`
  - `@Before` and `@After` advices
- Clean separation of concerns
- Console-based execution (no web, no database)

---

## Tech Stack

- Java
- Maven
- Spring Core (`spring-context`)
- Spring AOP (`spring-aop`)
- AspectJ annotations

---

## Project Structure

