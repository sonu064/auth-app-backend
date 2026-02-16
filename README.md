# 🚀 Production Ready Authentication Application

A complete **Production-Ready Authentication & Authorization System** built using **Spring Boot**.
This project demonstrates secure backend development practices including JWT authentication, OAuth2 login (Google & GitHub), REST API design, database integration, and Spring Security configuration.

This project is designed as a **real-world backend foundation** for scalable web applications.

---

## 📌 Why This Project?

Authentication is the core of every modern application.
This project covers:

* Secure User Registration & Login
* JWT-based Authentication
* Refresh Token Implementation
* OAuth2 Login (Google & GitHub)
* Spring Security Configuration
* RESTful API Design
* Database & ORM Integration
* Production-Level Architecture

---

## 🛠️ Tech Stack

* **Java 17+**
* **Spring Boot**
* **Spring Security**
* **JWT (JSON Web Token)**
* **OAuth2 (Google & GitHub Login)**
* **Hibernate / JPA**
* **MySQL**
* **Connection Pooling (HikariCP)**
* **Maven**

---

## 📚 Topics Covered in This Project

### 1️⃣ APIs & REST APIs

* RESTful architecture
* HTTP methods (GET, POST, PUT, DELETE)
* Status codes & best practices
* JSON request/response handling
* Layered architecture (Controller → Service → Repository)

---

### 2️⃣ Database & ORM

* MySQL database configuration
* JPA & Hibernate
* Entity mappings
* One-to-Many / Many-to-Many relationships
* Connection pooling using HikariCP
* Transaction management

---

### 3️⃣ Entities, Mappings & Repositories

* Proper entity design
* @Entity, @Table, @Id usage
* @OneToMany, @ManyToOne, @ManyToMany
* Spring Data JPA repositories
* Custom query methods

---

### 4️⃣ User Registration API

* Secure password storage using BCrypt
* Validation
* Duplicate user handling
* Role assignment

---

### 5️⃣ Spring Security Configuration

* Custom SecurityFilterChain
* Stateless session management
* Endpoint authorization rules
* CSRF configuration

---

### 6️⃣ JWT Authentication

* JWT token generation
* Token validation
* Claims handling
* Stateless authentication

---

### 7️⃣ JWT Filter

* Custom OncePerRequestFilter
* Extracting token from header
* Setting authentication in SecurityContext

---

### 8️⃣ Login Endpoint

* Username/Email & Password authentication
* JWT generation on successful login
* Proper exception handling

---

### 9️⃣ Refresh Token Implementation

* Secure refresh token storage
* Access token regeneration
* Token expiration handling
* Logout & token invalidation strategy

---

### 🔟 OAuth2 Login (Google & GitHub)

* Login with Google
* Login with GitHub
* OAuth2 flow integration
* Mapping OAuth users to internal user system
* Secure redirection handling

---

## 🔐 Authentication Flow

1. User registers or logs in.
2. Server validates credentials.
3. Access token (JWT) is generated.
4. Refresh token is generated.
5. JWT is sent in Authorization header.
6. Protected APIs validate token using JWT filter.

---

## 📂 Project Structure

```
src/main/java
 ├── config
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── security
 └── filter
```

This structure follows clean architecture principles.

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Configure application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/db_name
spring.datasource.username=your_username
spring.datasource.password=your_password
```

3. Run the application

```
mvn spring-boot:run
```

4. Test APIs using Postman.

---

## 📌 Key Features

✔ Stateless Authentication
✔ Role-Based Authorization
✔ Secure Password Encoding
✔ Refresh Token Mechanism
✔ OAuth2 Social Login
✔ Production-Level Security Configuration
✔ Clean & Scalable Architecture

---

## 🧠 What You Learn From This Project

* How authentication works internally
* How JWT replaces session-based auth
* How Spring Security processes requests
* How OAuth2 integrates with backend
* How to build secure REST APIs
* How to design scalable backend systems

---

## 🎯 Future Improvements

* Email Verification
* Account Activation
* Forgot Password Flow
* Rate Limiting
* Docker Deployment
* CI/CD Integration

---

## 👨‍💻 Author

Built as a complete production-ready backend authentication system for learning and real-world implementation.

---

⭐ If you find this project useful, consider giving it a star.
