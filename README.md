# 🛍️ Shopping Mall Management System

A Spring Boot based Shopping Mall Management System developed to manage shopping mall operations efficiently. The application provides a structured backend for handling different users and mall-related activities.

## 📌 Features

- Mall Admin Management
- Shop Owner Management
- Customer Management
- Employee Management
- CRUD Operations
- Spring Boot MVC Architecture
- MySQL Database Integration
- Maven Project Structure
- RESTful Backend

## 🛠️ Technologies Used

- Java 21
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Eclipse / Spring Tool Suite (STS)

## 📂 Project Structure

```
src
 ├── main
 │   ├── java
 │   │    └── com.example.shoopingmallprojectmanagement
 │   └── resources
 │        ├── application.properties
 │        ├── static
 │        └── templates
 └── test
```

## ⚙️ Prerequisites

- Java JDK 21
- Maven
- MySQL Server
- Eclipse / Spring Tool Suite

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/shopping-mall-management-system.git
```

### 2. Open the Project

Import the project into Eclipse or Spring Tool Suite as an **Existing Maven Project**.

### 3. Configure Database

Open:

```
src/main/resources/application.properties
```

Update the following values:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/shoppingmalldb
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 4. Create Database

```sql
CREATE DATABASE shoppingmalldb;
```

### 5. Run the Application

Run:

```
ShoopingmallprojectmanagementApplication.java
```

The application will start on:

```
http://localhost:8080
```

## 📖 Modules

- Mall Admin
- Shop Owner
- Customer
- Employee

## 📈 Future Enhancements

- Authentication & Authorization
- Payment Gateway Integration
- Online Shop Booking
- Product & Inventory Management
- Sales Reports
- Dashboard & Analytics
- Email Notifications

## 🎯 Learning Outcomes

- Spring Boot Application Development
- MVC Architecture
- CRUD Operations
- REST API Development
- Database Connectivity using JPA & Hibernate
- Maven Project Management

## 👩‍💻 Author

**Nisha D**

---

⭐ If you found this project useful, consider giving it a star on GitHub.
