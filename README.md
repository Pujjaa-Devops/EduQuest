# 🎯 Exam Portal

An Online Exam Management System built with **Spring Boot 2.3.3**, **Angular CLI**, **MySQL (via XAMPP)**, and **Java 17**.

![Java](https://img.shields.io/badge/Java-17-orange) ![Spring Boot](https://img.shields.io/badge/SpringBoot-2.3.3-brightgreen) ![Angular](https://img.shields.io/badge/Angular-CLI-red) ![MySQL](https://img.shields.io/badge/MySQL-Database-blue)

---

## 🛠 Tech Stack

- **Frontend:** Angular CLI, Node.js, VS Code
- **Backend:** Java 17, Spring Boot 2.3.3, Spring Security, Eclipse IDE
- **Database:** MySQL (XAMPP)

---

## ✨ Features

- 🔒 Secure Authentication & Authorization with Spring Security
- 🧑‍💻 Admin Panel to manage Categories, Exams, Questions
- 📝 User Panel to attempt exams and view results
- ⚡ RESTful APIs with Spring Boot
- 📊 Role-based access control (Admin / User)
- 🎯 JWT Token Authentication (if used)

---

## 🚀 Getting Started

### Backend (Spring Boot)

1. Clone the repository
2. Open backend folder in **Eclipse IDE**
3. Configure `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/your_database
    spring.datasource.username=root
    spring.datasource.password=
    spring.jpa.hibernate.ddl-auto=update
    ```
4. Run the project:
    ```
    Right click -> Run as -> Spring Boot Application
    ```
5. Backend server will run on: `http://localhost:8080/`

---

### Frontend (Angular)

1. Navigate to frontend folder
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the Angular server:
    ```bash
    ng serve
    ```
4. Frontend will run on: `http://localhost:4200/`

---

## 📂 Project Structure

