# 🎬 FilmLibrary

A full-stack web application for browsing and filtering a movie collection. Built with **React** (frontend) and **Spring Boot** + **PostgreSQL** (backend).

---

## 🔧 Technologies

- **Frontend**: React, CSS Modules
- **Backend**: Spring Boot, Java, REST API
- **Database**: PostgreSQL

---

## 📁 Project structure

```
FilmLibrary/
├── frontend/   # React app
├── backend/    # Spring Boot + PostgreSQL
```

---

## 🚀 Getting Started

### 📦 Frontend

```bash
cd frontend
npm install
npm start
```

> Runs the app in development mode at `http://localhost:3000`

---

### 🖥 Backend

```bash
cd backend
./mvnw spring-boot:run
```

> Runs the backend server at `http://localhost:8080`

Make sure your PostgreSQL database is running and the credentials in `application.properties` are correct.

---

### 🗃 Example `application.properties`

```
spring.datasource.url=jdbc:postgresql://localhost:5432/filmlibrary
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
```

---

## ✨ Features

- Filter movies by title, genre, and rating
- Sort movies by title, genre, or rating
- Responsive UI with CSS modules
- Backend search and filter with RESTful API

---

## 🛡 License

MIT
