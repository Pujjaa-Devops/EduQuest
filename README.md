Exam Portal
Exam Portal is a full-stack web application designed for managing online examinations. It is built using Java, Spring Boot (2.3.3), Angular CLI, MySQL (via XAMPP), and follows secure backend configurations with Spring Security.

🛠️ Technologies Used
Frontend:

Angular CLI

Node.js

Visual Studio Code

Backend:

Java 17

Spring Boot 2.3.3 (Latest Configuration)

Spring Security

Eclipse IDE

Database:

MySQL (using XAMPP server)

✨ Features
User Registration and Login (with Role-Based Access Control)

Secure Authentication with Spring Security

Admin Panel to manage exams, categories, and questions

User Panel for taking exams and viewing results

Real-time updates and error handling

Responsive UI with Angular Material (optional if you used it)

JWT (JSON Web Token) Authentication (if applicable)

🖥️ Setup Instructions
Prerequisites:
Java 17 installed

Node.js and npm installed

Angular CLI installed globally

MySQL database (XAMPP server)

Eclipse IDE (for backend development)

VS Code (for frontend development)

Backend Setup (Spring Boot):
Clone the repository or download the source code.

Open the project in Eclipse IDE.

Configure application.properties to connect to your MySQL database:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
Run the project as a Spring Boot Application.

Backend will start on http://localhost:8080/.

Frontend Setup (Angular):
Open the frontend project in VS Code.

Install dependencies:

bash
Copy
Edit
npm install
Run the Angular development server:

bash
Copy
Edit
ng serve
Frontend will be running at http://localhost:4200/.

🛡️ Security Configurations
Implemented Spring Security to secure REST APIs.

Passwords are encrypted before storing in the database.

Protected routes based on user roles (ADMIN / USER).

Token-based authentication (JWT) used for secure login sessions (if used).

📂 Project Structure
css
Copy
Edit
exam-portal/
 ├── backend/ (Spring Boot)
 │    ├── src/main/java/com/examportal/
 │    ├── src/main/resources/
 │    └── pom.xml
 ├── frontend/ (Angular)
 │    ├── src/app/
 │    ├── angular.json
 │    └── package.json
📚 Future Enhancements
Add timer functionality during exams

Add multiple user roles (Instructor, Admin, Student)

Enable real-time exam proctoring features

Analytics Dashboard for Admins

Email Notifications after test submissions

🙌 Acknowledgements
Thanks to the open-source community and tools that made this project possible!
