# 🎯 Career Assessment Tool

A full-stack web application designed to help students evaluate their skills, analyze personality traits, and receive personalized career recommendations.

---

## 🚀 Overview

The **Career Assessment Tool** enables students to:

* Take skill-based and personality assessments
* Receive career recommendations based on performance
* Track their progress and results

It also provides an **Admin dashboard** to manage assessments, users, and results.

---

## 🛠️ Tech Stack

### 🔹 Backend

* Java + Spring Boot
* Spring Security
* Hibernate / JPA
* REST APIs
* MySQL (or any relational DB)

### 🔹 Frontend

* React.js
* Vite
* JavaScript (ES6+)
* HTML5 + CSS3

---

## ✨ Features

### 👨‍🎓 Student

* User Registration & Login
* Attempt Skill Assessments
* Personality Test
* View Results & Recommendations

### 👨‍🏫 Admin

* Manage Students & Users
* Create & Manage Assessments
* Review Student Submissions
* Provide Feedback & Remarks

### 📊 System

* Career Recommendation Engine
* Skill Analysis
* Notification System

---

## 📂 Project Structure

career-assessment-backend/ → Spring Boot Backend
career-assessment-frontend/ → React Frontend

---

## ⚙️ Installation & Setup

### 🔹 1. Clone Repository

```bash
git clone https://github.com/sharvandeep/career-Assessment-Backend-Frontend-.git
cd career-Assessment-Backend-Frontend-
```

---

### 🔹 2. Backend Setup

```bash
cd career-assessment-backend
```

#### Configure Database

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

#### Run Backend

```bash
mvn spring-boot:run
```

Backend runs at:

```
http://localhost:8080
```

---

### 🔹 3. Frontend Setup

```bash
cd career-assessment-frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🔗 API Integration

Make sure frontend is connected to backend API:

* Base URL: `http://localhost:8080/api`

---

## 📸 Screenshots (Add Here)

> *(You can add screenshots later to improve your project visibility)*

Example:

```
![Dashboard](screenshots/dashboard.png)
```

---

## 🧪 Testing

Backend:

```bash
mvn test
```

Frontend:

```bash
npm run build
```

---

## 📌 Future Improvements

* 🔐 JWT Authentication
* 📱 Mobile Responsiveness
* 📊 Advanced Analytics Dashboard
* 🌐 Deployment (AWS / Vercel / Render)

---

## 👨‍💻 Author

**Sharvandeep**

* GitHub: https://github.com/sharvandeep

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🧑‍💻 Contribute

---

## 📄 License

This project is open-source and available under the MIT License.
