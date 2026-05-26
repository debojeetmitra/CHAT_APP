# 💬 Real-Time Chat Application (MERN Stack)

A full-stack **real-time chat application** built using the MERN stack with modern technologies like **Socket.io**, **JWT Authentication**, **Zustand**, and now fully **Dockerized** using Docker & Docker Compose 🐳.

🔗 **Live Demo:** https://chat-app-uiqr.onrender.com

---

# 🚀 Features

## 🔐 Authentication & Authorization
- Secure login/signup using JWT

## 💬 Real-Time Messaging
- Instant messaging powered by Socket.io

## 🟢 Online User Status
- See who is online in real-time

## 🧠 Global State Management
- Managed efficiently using Zustand

## ⚙️ Error Handling
- Robust error handling on both client & server

## 🎨 Modern UI
- Built with TailwindCSS + DaisyUI

## 🐳 Dockerized Architecture
- Dockerized frontend & backend services
- Multi-container setup using Docker Compose

## 🚀 Deployment
- Fully deployed on Render

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Zustand
- TailwindCSS
- DaisyUI

## Backend
- Node.js
- Express.js
- MongoDB
- Socket.io
- JWT Authentication

## DevOps / Deployment
- Docker
- Docker Compose
- Render

---

# 📸 Screenshots

## 💬 Chat Interface
<img width="1440" height="900" alt="Chat Interface" src="https://github.com/user-attachments/assets/71fe868d-6918-45b3-92ca-97b31a735409" />

---

## 🟢 Profile Page
<img width="1440" height="900" alt="Profile Page" src="https://github.com/user-attachments/assets/b917f10d-f519-4e89-ace3-66c7b2ac616c" />

---

## 🔐 Login / Signup Page
<img width="1440" height="900" alt="Login Page" src="https://github.com/user-attachments/assets/d315cc49-dac5-44d0-81e7-c8a6987a285d" />

---

# 📂 Project Structure

```bash
frontend/    → React Frontend
backend/     → Node.js + Express Backend
docker-compose.yml
```

---

# ⚡ Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/CHAT_APP.git
cd CHAT_APP
```

---

# 🖥️ Run Locally

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# 🐳 Run with Docker

## Build & Start Containers

```bash
docker compose up --build
```

## Stop Containers

```bash
docker compose down
```

---

# 🔑 Environment Variables

Create a `.env` file inside the `backend` folder:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

# 🎯 Key Learnings

- Implemented real-time communication using WebSockets
- Understood JWT-based authentication flow
- Managed global state with Zustand
- Learned Docker & Docker Compose
- Worked with multi-container applications
- Improved debugging and deployment workflow
- Understood full-stack deployment on Render

---

# 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and improve it.

---

# 📬 Contact

If you have any questions or suggestions, feel free to reach out.

---

⭐ If you like this project, give it a star!
