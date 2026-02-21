### PassMAN — Backend API (Node.js + Express + MongoDB)

A robust and lightweight REST API handling encrypted password storage, built with Express.js and powered by MongoDB Atlas.

---

### 🚀 Live API Endpoint

🔗 Backend Deployment: https://passman-backend-9yfg.onrender.com/

---

### 🧩 Overview

The PassMAN Backend exposes essential API routes that allow the frontend to store and retrieve password entries.
It uses MongoDB Atlas for persistent storage and includes basic CRUD operations.

---

### 🛠️ Tech Stack

Node.js

Express.js

MongoDB Atlas

dotenv for environment variables

CORS for cross-origin access

Render for server deployment

---

### ✨ API Endpoints
Method	Route	Description
GET	/	Fetch all stored passwords
POST	/	Insert a new password entry
DELETE	/	Delete an existing password by ID

---

### 📁 Project Structure
Backend/
  ├── server.js
  ├── package.json
  ├── .env
  └── node_modules/

---  

### 📜 License

MIT License — open for public use.