# ⚽ Soccer 7 League – Fantasy Football Web App

🚀 A full-stack **Fantasy Football League Application** where users can explore players, teams, and build their ultimate squad.

🔴 **Live Demo:**
👉 https://soccer-7-league.netlify.app/

---

## 📸 Preview

<img width="1920" height="920" alt="live image" src="https://github.com/user-attachments/assets/a6caefb2-6fdf-48ed-9c0d-9b6bcb3200e7" />

---

## 🧠 Features

✨ Explore football players and teams
✨ Search players by name, position, or nation
✨ View detailed player stats
✨ Responsive UI for all devices
✨ Full-stack integration (Frontend + Backend + Database)
✨ Fast and dynamic data fetching

---

## 🏗️ Tech Stack

### 🔹 Frontend

* React.js (with React Router)
* SCSS (for styling)
* Axios (API calls)

### 🔹 Backend

* Spring Boot (Java)
* REST APIs

### 🔹 Database

* MySQL

### 🔹 Deployment

* Frontend → Netlify
* Backend → Render
* Database → MySQL Cloud

---

## ⚙️ Installation & Setup (Local)

### 1️⃣ Clone Repository

```bash
git clone https://github.com/akash-kumar-7-git/soccer-league-fantasy.git
cd soccer-league-fantasy
```

---

### 2️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

### 3️⃣ Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

---

### 4️⃣ Configure Database

Update your `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db      /create your own
spring.datasource.username=root                                /create your own
spring.datasource.password=your_password                       /create your own
```

---

## 🔗 API Integration

Make sure your frontend API URL points to backend:

```js
const BASE_URL = "https://league-backend-production-0d9d.up.railway.app/";
```

---

## 📁 Project Structure

```
project-root/
│
├── frontend/        # React App
├── backend/         # Spring Boot API
├── database/        # MySQL Schema
└── README.md
```

---

## 🚀 Deployment Guide

### Frontend (Netlify)

* Connect GitHub repo
* Build command: `npm run build`
* Publish directory: `build`

### Backend (Railway)

* Build: `mvn clean install`
* Start: `java -jar target/app.jar`

---

## 💡 Future Improvements

🔹 User Authentication (Login/Register)
🔹 Create Fantasy Team Feature
🔹 Player Ranking System
🔹 Admin Dashboard
🔹 Real-time match updates

---

## 👨‍💻 Author

**Akash Kumar**

* GitHub: https://github.com/akash-kumar-7-git
* LinkedIn: ([Add your profile here](https://www.linkedin.com/in/akash-kumar-singh-9a8363314/))

---

## ⭐ Show Your Support

If you like this project:

🌟 Star this repository
🍴 Fork it
📢 Share with others

---

## 📢 Note

This project is built for **learning + portfolio purposes** and demonstrates full-stack development skills.

---

🔥 *Built with passion for football & coding*
