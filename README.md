# QuizApp – Spring Boot REST API

A backend REST API for a Quiz Application built using **Spring Boot, Spring Data JPA, Hibernate, and PostgreSQL**.

The application provides APIs to manage quiz questions, create quizzes dynamically based on categories, retrieve quizzes, and submit quizzes for evaluation.

---

## 🚀 Features

- Create and manage quiz questions
- Retrieve all questions
- Retrieve questions by category
- Dynamically generate quizzes
- Select number of questions for a quiz
- Retrieve generated quizzes
- Submit quiz answers
- Automatically calculate quiz score
- PostgreSQL database integration
- RESTful API architecture
- CORS configuration for frontend integration

---

## 🛠️ Tech Stack

- **Java 17+**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **Hibernate**
- **PostgreSQL**
- **Maven**
- **Lombok**
- **Postman** for API testing

---

## 📂 Project Structure

```text
Quizzapp/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── Ravikiran/
│   │   │           └── Quizzapp/
│   │   │               ├── Controller/
│   │   │               ├── Model/
│   │   │               ├── Repository/
│   │   │               ├── Service/
│   │   │               └── QuizzappApplication.java
│   │   │
│   │   └── resources/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
└── README.md
