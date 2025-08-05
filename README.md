# Student-Intern-Website
# 🌟Student Intern Dashboard – She Can Foundation

This is a demo internship dashboard built by **Megha Rathi** as part of the She Can Foundation internship.  
The project includes both a frontend (HTML/CSS/JS) and backend (Node.js) with dummy API integration.

---

## 📌 Features

### 🖥️ Frontend:
- Dummy Login Page (no authentication)
- Dashboard displaying:
  - Intern name (fetched from backend)
  - Referral code (fetched from backend)
  - Total donations raised (fetched from backend)
  - Rewards / Unlockables (static)
- Leaderboard page showing top interns (fetched from backend)

### 🔙 Backend:
- REST API built with **Node.js + Express**
- Serves dummy JSON data for user and leaderboard
- CORS enabled, works with frontend fetch

---

## 🚀 API Endpoints

| Method | Endpoint               | Description                  |
|--------|------------------------|------------------------------|
| GET    | `/api/user`            | Returns intern info          |
| GET    | `/api/leaderboard`     | Returns leaderboard list     |

---

## 📁 Project Structure
📂 Project Root/
├── shecan-backend/
│ ├── server.js
│ ├── package.json
│ └── README.md
├── Student_Intern_Website/
│ ├── dashboard.html
│ ├── leaderboard.html
│ ├── indrex.html
│ ├── style.css
│ ├── videos.mp4
│ └── tempsnip.png
└── screenshots/
├── login-page.png
├── dashboard.png
├── leaderboard.png
├── backend-terminal.png
└── api-response.png


---

## 🧪 How to Run the Project

### 🔹 Backend

```bash
cd shecan-backend
npm install
node server.js
Runs at: http://localhost:3000

🔹 Frontend

Open Student_Intern_Website folder in VS Code
Right-click dashboard.html → Open with Live Server
OR open in browser:
http://127.0.0.1:5500/dashboard.html

🙋‍♀️ Developed By
Megha Rathi
MCA Student, AKTU


