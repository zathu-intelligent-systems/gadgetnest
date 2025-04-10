# E-Commerce Backend API

This is a Spring Boot-powered backend for an e-commerce platform designed to sell tech devices. It features secure user authentication using JWT, Stripe payment integration, PostgreSQL for data storage, and local image handling.

---

## Authors

**John Kabatika Chirwa (Backend Developer)** <br>
Email: [kingmlowoka16@outlook.com](mailto:kingmlowoka16@outlook.com) <br>
Phone: +265 998 21 24 66 / +265 881 88 94 87 <br>
LinkedIn: [https://linkedin.com/in/king-mlowoka-a7813a320](https://linkedin.com/in/king-mlowoka-a7813a320) <br>
WhatsApp: [Chat on WhatsApp](https://wa.me/265881889487) <br>

---

## Features

- RESTful APIs built with Spring Boot
- JWT-based Authentication using Spring Security
- CRUD operations for products, categories, users, orders
- Stripe integration for payment processing
- PostgreSQL for relational data storage
- Local file uploads and image resizing using Thumbnailator
- Password hashing with BCrypt
- DTO mapping and input validation
- Unit and integration testing

---

## Getting Started

### Prerequisites

- Java 17+
- Maven 3.8+
- PostgreSQL installed and running
- (Optional) Docker (for containerization)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-ecommerce-backend.git
cd your-ecommerce-backend
```

### 2. Setup Your Database

```bash
CREATE DATABASE ecommerce_db;
```

Update your application.properties or application.yml:

```bash
spring.datasource.url=jdbc:postgresql://localhost:5432/ecommerce_db
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
```

### 3. Run the Application

```bash
./mvnw spring-boot:run
```

Or build the JAR and run it:

```bash
./mvnw clean package
java -jar target/ecommerce-backend-0.0.1-SNAPSHOT.jar
```
---

## Folder Structure

```
gadgetnest/
│── backend/                     # Spring Boot Backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/gadgetnest/
│   │   │   │   ├── controllers/         # API Controllers
│   │   │   │   ├── services/            # Business Logic
│   │   │   │   ├── repositories/        # Database Repositories
│   │   │   │   ├── models/              # Entities/DTOs
│   │   │   │   ├── security/            # JWT & Auth Configs
│   │   │   │   ├── exceptions/          # Custom Exception Handling
│   │   │   │   ├── GadgetNestApplication.java         # Main App
│   │   │   ├── resources/
│   │   │   │   ├── application.properties             # Backend Configs
│   │   ├── test/               # Unit & Integration Tests
│   ├── Dockerfile              # Backend Docker Config
│   ├── pom.xml                 # Maven Dependencies
│   ├── README.md               # Backend Documentation
│
│── frontend/                   # React Frontend
│   ├── public/                 # Public Assets (index.html, favicon)
│   ├── src/
│   │   ├── components/         # Reusable Components (Navbar, Footer, etc.)
│   │   ├── pages/              # Pages (Home, Product, Checkout)
│   │   ├── hooks/              # Custom React Hooks
│   │   ├── context/            # State Management (React Context API)
│   │   ├── services/           # API Calls to Backend
│   │   ├── App.js              # Main App Component
│   │   ├── index.js            # React Entry Point
│   ├── package.json            # Dependencies
│   ├── Dockerfile              # Frontend Docker Config
│   ├── README.md               # Frontend Documentation
│
│── database/                   # Database Configurations
│   ├── init.sql                # Initial Schema & Sample Data
│   ├── migrations/             # Database Migrations
│
│── docker-compose.yml          # Docker Configuration for Backend & Frontend
│── .gitignore                  # Git Ignore for Unnecessary Files
│── README.md                    # Project Overview & Setup Guide
```
---

## Dependencies Used

### Backend

**Framework & Core**
- Spring Boot Starter Web
- Spring Boot Starter Data JPA
- Spring Boot DevTools

**Database & ORM**
- PostgreSQL Driver
- Hibernate Core

**Authentication & Security**
- Spring Boot Starter Security
- Java JWT (Auth0)
- Spring Security Crypto (BCrypt)

**File Uploads & Image Handling**
- Thumbnailator

**Payment Integration**
- Stripe Java SDK

**Code Simplification**
- Lombok

**For Productivity**
- Spring Boot Starter Validation (input validation)
- MapStruct (DTO mapping)
- Spring Boot Starter Actuator (monitoring)
- SLF4J (logging)
- Spring Boot Starter Test (JUnit, Mockito, etc.)