# 🧾 Udhaar Management System

A web-based platform to **digitally manage udhaar (credit) transactions** between sellers and buyers.  
It simplifies tracking of outstanding balances, pending claims, and payments — replacing manual ledgers with a secure, real-time digital system.

---

## 🚀 Features

- 🔐 **Secure Authentication (JWT-based)**
- 👥 **Role-based access** for Sellers and Buyers
- 💸 **Add, confirm, and settle transactions**
- 🧾 **Manage inventory and customer records**
- 📊 **Interactive dashboard** showing balances and claims
- 🔄 **Real-time updates** using REST APIs
- 📱 **Responsive UI** for mobile and desktop

---

## 🛠️ Tech Stack

**Frontend**
- HTML5, CSS3, JavaScript  
- TailwindCSS (for styling)  
- Chart.js (for dashboard visualization)

**Backend**
- Node.js + Express.js  
- MongoDB (Mongoose ODM)  
- JSON Web Tokens (JWT)  
- bcryptjs for password hashing  

---

## ⚙️ System Architecture

```

Frontend (HTML, CSS, JS)
↓ REST API
Backend (Node.js + Express)
↓
Database (MongoDB)

```

---

## 🧩 Project Structure

```

Udhaar-Management-System/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── scripts/
│   ├── styles/
│   └── assets/
│
└── README.md

````

---

## 🧰 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/Udhaar-Management-System.git
cd Udhaar-Management-System
````

### 2️⃣ Install dependencies

```bash
cd backend
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the `backend/` directory with:

```env
PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the backend server

```bash
npm start
```

### 5️⃣ Open the frontend

Simply open `frontend/index.html` in your browser or use a local server.

---

## 📦 API Overview

| Endpoint            | Method   | Description                  |
| ------------------- | -------- | ---------------------------- |
| `/api/auth/signup`  | POST     | Register a new user          |
| `/api/auth/login`   | POST     | Login and get JWT            |
| `/api/transactions` | GET/POST | Manage udhaar transactions   |
| `/api/inventory`    | GET/POST | Manage shop inventory        |
| `/api/dashboard`    | GET      | Fetch user dashboard summary |

---

## 💡 Purpose

To provide a **digital solution for local shopkeepers** to manage their udhaar system easily and transparently — ensuring both parties have access to clear transaction histories and balances.

---

## 👨‍💻 Author

**Aarti Pal**

---

## 🪪 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute it with attribution.

---
