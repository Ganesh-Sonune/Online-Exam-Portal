# 📘 Online Exam Portal 

[![Spring Boot](https://img.shields.io/badge/SpringBoot-2.6.5-green.svg)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)](https://www.mysql.com/)
[![JWT](https://img.shields.io/badge/Security-JWT-red.svg)](https://jwt.io/)
[![Maven](https://img.shields.io/badge/Build-Maven-yellow.svg)](https://maven.apache.org/)

An **Online Exam Portal** built with **Spring Boot, MySQL, Spring Security (JWT), and Hibernate/JPA**.  
This project allows **Admins** to manage exams and **Students** to attempt quizzes, submit answers, and view results.  

---

## 🚀 Features
✅ 👨‍🎓 **Student Module** → Attempt quizzes, view results, and track performance  
✅ 🛠️ **Admin Module** → Manage categories, quizzes, and questions (CRUD)  
✅ 🔐 **Authentication & Authorization** → Secure login using **Spring Security + JWT**  
✅ 🗄️ **Database Integration** → MySQL with Hibernate/JPA ORM  
✅ 📊 **Result Tracking** → Store & evaluate user performance  

---

## 🏗️ Tech Stack
- ⚡ **Backend**: Spring Boot, Spring Security, Spring Data JPA  
- 🗄️ **Database**: MySQL  
- 🔑 **Authentication**: JWT (JSON Web Token)  
- 📦 **Build Tool**: Maven  
- 💻 **IDE**: IntelliJ / VS Code / Eclipse  

---

## 📂 Project Structure
```bash
ExamPortal/
 ┣ src/main/java/com/
 ┃ ┣ controller/     # REST Controllers
 ┃ ┣ model/          # Entities (User, Role, Quiz, Question, Result...)
 ┃ ┣ service/        # Service Layer
 ┃ ┗ config/         # Security & JWT Configuration
 ┣ src/main/resources/
 ┃ ┣ application.properties  # DB Config
 ┃ ┗ static/templates        # (Optional - Frontend templates)
 ┣ pom.xml
```
---

## ⚙️ Installation & Setup

### 🔹 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/exam-portal.git
cd exam-portal

### 🔹 2️⃣ Configure MySQL Database
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/examportal
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```
### 🔹 3️⃣ Run the application
```bash
mvn spring-boot:run
```
### 🔹 4️⃣ Access APIs
```bash
🌍 Swagger/Postman → http://localhost:8080
```
---

## 👨‍💻 Author  
**Ganesh Sonune**  
📧 ganusonune4@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ganesh-sonune/)
