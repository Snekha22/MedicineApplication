# 💊 Medicine Application

A comprehensive full-stack web application developed to manage patients, medicines, and appointment scheduling within a healthcare environment. This project showcases complete integration of Spring Boot (Java), MySQL, JWT-based security, and a responsive front end using Thymeleaf and Bootstrap. Designed with clean code architecture, it follows modern development practices and is ideal for demonstrating practical Java Full Stack development skills.

---

## 📌 Overview

This application enables users (patients) to:

- Register and log in securely
- Book and manage doctor appointments
- View their booking history
- Manage personal medication records

Admins or healthcare providers can:

- View all appointments and patient data
- Manage medicine details
- Maintain a smooth and organized flow of healthcare operations

---

## ✨ Key Features

- 🔐 Secure Authentication & Authorization using JWT
- 👨‍⚕️ User Registration and Login with Role-based Access
- 📅 Appointment Booking System
- 💊 Medicine Management with Add/View/Delete functionalities
- 🧾 Appointment History & Profile Dashboard
- 📘 API Documentation via Swagger (OpenAPI 3)
- 💻 Responsive UI using Thymeleaf + Bootstrap

---

## 🛠 Tech Stack

| Layer          | Technology                     |
|----------------|---------------------------------|
| **Backend**    | Java 17, Spring Boot, Spring Security, Spring Data JPA |
| **Database**   | MySQL                          |
| **Frontend**   | Thymeleaf, HTML5, CSS3, JavaScript, Bootstrap 5 |
| **Tools**      | Maven, Swagger, Eclipse, Postman |

---

## 📁 Project Structure

```plaintext
MedicineApplication/
├── src/
│   └── main/
│       ├── java/com/medicineapp/
│       │   ├── controller/       --> REST & Page Controllers
│       │   ├── model/            --> JPA Entities (User, Appointment, Medication)
│       │   ├── repository/       --> Spring Data JPA Interfaces
│       │   ├── service/          --> Business Logic Layer
│       │   └── config/           --> JWT & Security Configuration
│       └── resources/
│           ├── static/           --> CSS / JS
│           ├── templates/        --> Thymeleaf HTML Pages
│           └── application.properties
├── pom.xml
└── README.md
```
---
## ⚙️ Installation & Setup
Prerequisites
- Java 17+
- MySQL 8+
- Maven 3.6+
- IDE (IntelliJ / Eclipse)
- Git

---
## Steps
1. Clone the Repository
```
git clone https://github.com/Snekha22/MedicineApplication.git
cd MedicineApplication
```

2. Create MySQL Database
```
sql
CREATE DATABASE medicine_db;
```
3. Update Configuration
Open ``` src/main/resources/application.properties```  and update:
```
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
```
4. Run the Application
Using IDE: Run ```MedicineApplication.java```
Using CLI:
```
mvn spring-boot:run
```
5. Access the Application
```
UI: http://localhost:8080
Swagger UI: http://localhost:8080/swagger-ui/index.html
```
---
## 📸 Screenshots
<img width="1919" height="956" alt="image" src="https://github.com/user-attachments/assets/ae257a2e-8bf8-4ddd-aad3-fcc3acdb6a7a" />
<img width="1918" height="957" alt="image" src="https://github.com/user-attachments/assets/f270f67a-390f-448f-a898-2e7f46c72fd4" />
<img width="1919" height="956" alt="image" src="https://github.com/user-attachments/assets/80afd47a-cead-4e16-85d8-64ea793b8f9f" />
<img width="1919" height="954" alt="image" src="https://github.com/user-attachments/assets/cd67a632-31c5-4f12-8dfa-26275cef72e0" />
<img width="1916" height="970" alt="image" src="https://github.com/user-attachments/assets/9b7b7768-62fc-4ba3-85d0-2c32622535cd" />
<img width="1919" height="951" alt="image" src="https://github.com/user-attachments/assets/a7824bce-068f-46c0-bf29-c8b65c66df2c" />
<img width="1905" height="965" alt="image" src="https://github.com/user-attachments/assets/16a1a23d-97d4-4da7-91f9-be43db022c2e" />
<img width="1918" height="956" alt="image" src="https://github.com/user-attachments/assets/76cb8fa5-9366-484c-88c2-cea72b3a6769" />









