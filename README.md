# 📚 Book Shop API

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![Spring Security](https://img.shields.io/badge/Spring-Security-green)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub%20Actions-success)

A RESTful **Book Shop API** built with **Spring Boot** that provides authentication, book catalog management, shopping cart functionality, and category management. The project follows a layered architecture with DTOs, exception handling, Docker support, and CI/CD integration.

---

# ✨ Features

- 📚 Book Management
- 🗂️ Category Management
- 👤 User Authentication
- 🛒 Shopping Cart
- 🔐 Secure Login
- 📦 RESTful API
- 🐳 Docker Support
- ⚙️ GitHub Actions CI
- 📬 Postman Collection

---

# 🏗️ Architecture

```text
                 Client
                    │
                    ▼
          REST Controllers
                    │
                    ▼
             Service Layer
                    │
                    ▼
          Spring Data JPA
                    │
                    ▼
              MySQL Database
```

---

# 📂 Project Structure

```
Book-shop-api/
├── controller/
├── dto/
├── entities/
├── repository/
├── service/
├── config/
├── exception/
├── postman/
├── Dockerfile
├── docker-compose.yaml
└── pom.xml
```

---

# 📖 Main Modules

## Authentication

- User login
- User registration
- Authentication endpoints

---

## Books

- Add books
- Update books
- Delete books
- Browse catalog

---

## Categories

- Create categories
- Update categories
- View categories

---

## Shopping Cart

- Add items
- Remove items
- Update quantities
- View cart

---

# 🛠️ Technologies

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Security
- MySQL
- Maven
- Docker
- GitHub Actions

---

# 🚀 Getting Started

## Clone

```bash
git clone https://github.com/medelafia/Book-shop-api.git

cd Book-shop-api
```

---

## Run with Docker

```bash
docker compose up --build
```

---

## Run locally

```bash
mvn spring-boot:run
```

---

# 📬 API Testing

A Postman collection is included under:

```
postman/BookShop.postman_collection.json
```

Import it into Postman to test all available endpoints.

---

# 📈 Future Improvements

- JWT Authentication
- Refresh Tokens
- Order Management
- Payment Integration
- Product Reviews
- Wishlist
- Search & Pagination
- Redis Cache
- Swagger/OpenAPI
- Unit & Integration Tests
- Kubernetes Deployment

---

# 🎯 Learning Objectives

This project demonstrates:

- REST API development
- Spring Security
- DTO-based architecture
- Exception handling
- Docker containerization
- CI/CD with GitHub Actions
- CRUD operations with JPA

---

# 👥 Contributors

This project was developed collaboratively as part of a team effort.

### 💻 Application Development
- **Douae El Yousfi** – Backend development and application implementation
- **Ismail El Bouzidi** – Backend development and application implementation

### 🚀 Deployment & DevOps
- **Mohamed El Afia** - Docker & Docker Compose - CI/CD pipeline (GitHub Actions) - Deployment configuration

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
