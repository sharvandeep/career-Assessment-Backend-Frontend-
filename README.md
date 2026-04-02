🎯 Career Assessment & Skill Analysis Platform

A full-stack web application that helps students analyze their skills, identify strengths & weaknesses, and receive personalized career recommendations based on assessment performance.

---

🚀 Problem Statement

Traditional quiz systems only provide scores.
They do not analyze skills or guide career decisions.

This project solves that by building a:

«✅ Career Assessment Platform that evaluates student performance, identifies skill gaps, and suggests suitable career paths.»

---

🧠 Key Objectives

- Analyze student performance beyond scores
- Identify strong & weak subject areas
- Provide career recommendations
- Help faculty track student progress
- Build a data-driven assessment system

---

🛠️ Tech Stack

🔹 Backend

- Java + Spring Boot
- Spring Security
- Hibernate / JPA
- REST APIs
- MySQL

🔹 Frontend

- React.js
- Vite
- JavaScript (ES6+)
- HTML5 + CSS3

---

✨ Core Features

👨‍🎓 Student Module

- 🔐 User Registration & Login
- 📝 Attempt Skill-Based Assessments
- 📊 View Results & Performance Analysis
- 📈 Track Progress Over Time
- 🎯 Get Career Recommendations
- 📚 View Assessment History

---

👨‍🏫 Faculty Module

- 🛠️ Create & Manage Assessments
- 👨‍🎓 Monitor Student Performance
- 📊 View Results & Analytics
- 🔍 Review Student Answers
- 📈 Identify Weak & Strong Areas

---

📊 System Features

- 🧠 Skill Analysis Engine
- 🎯 Career Recommendation System
- 📉 Performance Tracking
- 🔔 Notification System
- 🔐 Role-Based Access Control

---

🧩 System Workflow

👨‍🎓 Student Flow

1. Login / Register
2. View Available Assessments
3. Attempt Assessment
4. Get Results
5. View:
   - Score & Percentage
   - Strengths
   - Weak Areas
   - Career Suggestions
6. Track History

---

👨‍🏫 Faculty Flow

1. Login
2. Create Assessment
3. View Student Attempts
4. Analyze Performance
5. Improve Assessment Quality

---

📂 Project Structure

career-assessment-backend/   → Spring Boot Backend
career-assessment-frontend/  → React Frontend

---

⚙️ Installation & Setup

🔹 1. Clone Repository

git clone https://github.com/sharvandeep/career-Assessment-Backend-Frontend-.git
cd career-Assessment-Backend-Frontend-

---

🗄️ Database Setup (MySQL)

Step 1: Create Database

CREATE DATABASE career_assessment_db;

---

Step 2: Configure Backend

Edit:

career-assessment-backend/src/main/resources/application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/career_assessment_db
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

---

Step 3: Run Backend

cd career-assessment-backend
mvn spring-boot:run

Backend runs at:

http://localhost:8080

---

Step 4: Run Frontend

cd career-assessment-frontend
npm install
npm run dev

Frontend runs at:

http://localhost:5173

---

🔗 API Configuration

Ensure frontend is connected to backend:

http://localhost:8080/api

---




🧪 Testing

Backend

mvn test

Frontend

npm run build

---

🚀 Future Enhancements

- 🔐 JWT Authentication
- 📊 Advanced Analytics (Charts)
- 📱 Mobile Responsiveness
- 🌐 Cloud Deployment (AWS / Vercel / Render)
- 🤖 AI-based Career Recommendation

---

👨‍💻 Author

Sharvandeep

- GitHub: https://github.com/sharvandeep

---

⭐ Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork it
- 🤝 Contribute

---

📄 License

This project is open-source and available under the MIT License.
