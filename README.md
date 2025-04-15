#  Contact Management System API

A full-featured, scalable backend API developed using **Java**, **Spring Boot**, and **MySQL**, designed to manage and store user contact information. This RESTful API follows clean architecture principles, making it extensible and easy to integrate with any frontend or mobile client.

---

##  Project Overview

This application allows users to perform typical CRUD operations on contact records. It can serve as the backend for a contact management web or mobile application.

Each contact can contain:
- Full name
- Phone number
- Email address
- Location details (optional)

Future-ready design makes it easy to plug in features like:
- Search & filter
- User authentication (JWT or OAuth2)
- Export to CSV or PDF
- Contact tags or groups
- Email notifications or reminders

---

##  Technologies Used

| Technology        | Description                               |
|-------------------|-------------------------------------------|
| Java              | Core programming language                 |
| Spring Boot       | Backend framework (RESTful architecture) |
| MySQL             | Relational database                       |
| Maven             | Build automation tool                     |
| Lombok            | Simplifies Java boilerplate code          |
| Postman           | API testing tool                          |
| Git & GitHub      | Version control                           |

---

##  Architecture

- **Controller layer** handles incoming HTTP requests and sends responses.
- **Service layer** contains the business logic.
- **Repository layer** interacts with the MySQL database using Spring Data JPA.
- **Model layer** defines entity classes for contact data.
- **Validation layer** ensures input correctness.

---

##  REST API Endpoints

| Method | Endpoint           | Description             |
|--------|--------------------|-------------------------|
| GET    | `/api/contacts`     | Fetch all contacts      |
| GET    | `/api/contacts/{id}`| Fetch a single contact  |
| POST   | `/api/contacts`     | Add a new contact       |
| PUT    | `/api/contacts/{id}`| Update a contact        |
| DELETE | `/api/contacts/{id}`| Delete a contact        |

 endpoints return data in **JSON** format.

------*