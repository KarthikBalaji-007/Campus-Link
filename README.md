# 🌐 CampusLink – A Centralized Student Utility Hub

> 🚀 **Domain:** Campus Utilities  
> 🧠 **Built For:** Enhancing student productivity and campus management  
> 🛠️ **Tech Stack:** MERN (MongoDB, Express.js, React.js, Node.js) / Firebase (optional for auth)  

---
![Project Type](https://img.shields.io/badge/Project-Campus%20Utilities-orange?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-React.js-blue?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-Node.js%20|%20Express.js-yellow?style=for-the-badge)
![Database](https://img.shields.io/badge/Database-MongoDB-brightgreen?style=for-the-badge)
![Authentication](https://img.shields.io/badge/Auth-JWT%20%2F%20Firebase-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)


## 📌 Objective

CampusLink aims to **centralize essential campus services** into a single web application. It simplifies everyday tasks for students and administrators, boosting communication, accessibility, and productivity inside a college campus.

---

## 🎯 Core Features (First 4 Hours MVP)

### 📢 1. Campus Announcements Feed
- ✅ Admin can post official updates like:
  - College events
  - Exam schedules
  - Holiday notices
- 🔎 Students can view categorized announcements
- 📅 Sorted by date and relevance

---

### 🧳 2. Lost & Found Section
- 🎒 Students can **report** lost/found items
- 📍 Include:
  - Item name
  - Description
  - Image upload
  - Location and date
- 🔍 **Smart filters**:
  - Category-based (e.g., electronics, ID cards, stationery)
  - Date range search

---

### 📅 3. Mini Timetable Scheduler
- 🧑‍🎓 Students can:
  - Input their weekly class timetable
  - View it in a **calendar/grid** format
- ✏️ Features:
  - Edit and delete options
  - Responsive layout for mobile view

---

### 🛠️ 4. Hostel Complaint Registration
- 🏠 Raise issues like:
  - Water problems
  - Electricity outages
  - Room cleaning
- 📊 Track complaint status:
  - `Pending`, `In-Progress`, `Resolved`
- 👨‍💼 Admin panel to manage and resolve complaints

---

### 🔐 5. User Authentication System
- 👥 Roles: `Student` and `Admin`
- 🧾 Secure **login/signup** system
- 🔐 Role-based access to pages/features
- 🔄 Session Management via:
  - **JWT (JSON Web Tokens)**  
  - or **Firebase Authentication**

---

## 🗂️ Folder Structure (Suggested)

```
campuslink/
├── client/                   # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.js
│   └── package.json
├── server/                   # Express Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .env
├── README.md
└── package.json
```

---

## 🔧 Future Enhancements (Post-Hackathon Ideas)

- 📱 Push notifications for announcements
- 🧾 Complaint history for students
- 📚 Integration with academic calendar / syllabus
- 🗂 Admin dashboard analytics
- 📥 File upload for timetable import (Excel/PDF)

---

## 🤝 Team Roles

| Name | Role |
|------|------|
| Backend Lead | Authentication, APIs, Database |
| Frontend Dev | UI/UX for all core features |
| Full Stack Dev | Timetable + Complaints |
| QA / Tester | Ensuring everything works |
| PM / Presenter | Coordinating, pitch-ready |

---

## ⚙️ Technologies Used

- Frontend: **React.js, Tailwind CSS**
- Backend: **Node.js, Express.js**
- Database: **MongoDB**
- Authentication: **JWT / Firebase Auth**
- Deployment: **Render / Vercel / Netlify**

---

## 📸 UI Sneak Peek (Add Screenshots Here)
> _Once available, paste UI screenshots for each feature here._

---

## 📃 License

This project is licensed under the MIT License.  
Feel free to fork, contribute, and enhance it for your own campus!

---

## ✨ Contributing

Contributions are welcome!  
If you have ideas for new features, open an issue or submit a pull request.

---

> **Made with ❤️ by Team CampusLink**
