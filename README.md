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

⚙️ Installation & Setup Guide

Follow these steps to run the project on your local machine.

---

🔹 Step 1: Clone Repository

git clone https://github.com/sharvandeep/career-Assessment-Backend-Frontend-.git

cd career-Assessment-Backend-Frontend-

---

🗄️ Step 2: Setup MySQL Database

Open MySQL Workbench

- Start MySQL Workbench
- Connect to your local server

Create Database

CREATE DATABASE career_assessment_db;

---

🔹 Step 3: Configure Backend

cd career-assessment-backend

Open file:

src/main/resources/application.properties

Update:

spring.datasource.url=jdbc:mysql://localhost:3306/career_assessment_db

spring.datasource.username=your_username

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true

---

🔹 Step 4: Run Backend

mvn clean install

mvn spring-boot:run

Backend runs at:

http://localhost:8080

---

🔹 Step 5: Run Frontend

Open new terminal:

cd career-assessment-frontend

npm install

npm run dev

Frontend runs at:

http://localhost:5173

---

🔗 Step 6: API Configuration

Ensure frontend API base URL:

http://localhost:8080

---

🌐 Step 7: Open Application

Open in browser:

http://localhost:5173

---

⚠️ Common Issues & Fixes

❌ Port Already in Use

server.port=8081

---

❌ MySQL Connection Error

- Check username/password
- Ensure MySQL is running

---

❌ Node Modules Error

npm install

---

❌ Maven Not Found

./mvnw spring-boot:run

---

🧪 Testing

Backend

mvn test

Frontend

npm run build

---

📊 Key Differentiation

Feature| Quiz App| This System
Score Display| ✅| ✅
Skill Analysis| ❌| ✅
Weak Area Detection| ❌| ✅
Career Recommendation| ❌| ✅
Progress Tracking| ❌| ✅
Faculty Analytics| ❌| ✅

---

📸 Screenshots

«Add screenshots here for better presentation»

![Student Dashboard](screenshots/student-dashboard.png)
![Faculty Dashboard](screenshots/faculty-dashboard.png)

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
