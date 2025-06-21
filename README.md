# 📝 Daily Task Tracker

A simple and efficient Spring Boot application to help users manage their daily tasks. The application allows users to create, update, delete, and view tasks. Users can also filter tasks based on status (e.g., pending, completed) and due date.

---

## 🚀 Features

- ✅ Create, Read, Update, and Delete tasks
- 📅 Filter tasks by **status** and **due date**
- 🔗 RESTful API endpoints using Spring Boot
- 💾 Data persistence using Spring Data JPA
- 🔍 API tested using Postman

---

## 🧑‍💻 Technologies & Tools

- **Java 17+**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **H2 / MySQL Database** (switchable)
- **Maven**
- **IntelliJ IDEA**
- **Postman**

---

## 📁 Project Structure

daily-task-tracker/
│
├── src/
│ ├── main/
│ │ ├── java/com/example/tasktracker/
│ │ │ ├── controller/
│ │ │ ├── entity/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── TaskTrackerApplication.java
│ │ └── resources/
│ │ ├── application.properties
│ │ └── data.sql (optional)
│ └── test/...
│
├── pom.xml
└── README.md
