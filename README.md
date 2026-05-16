# Smart Emergency SOS System 🚨

A real-time emergency response web application built using the MERN stack that enables users to send instant SOS alerts with live GPS location tracking and Google Maps integration for rapid emergency communication.

---

## ✨ Features

- Real-time SOS alert system
- Live GPS location tracking
- Google Maps location sharing
- User authentication and authorization
- Emergency contact management
- Real-time communication using Socket.IO
- Responsive UI with Tailwind CSS
- Secure REST API integration
- MongoDB database management

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- Socket.IO
- JWT Authentication
- Bcrypt.js

### Database
- MongoDB
- Mongoose

---

# 📂 Project Structure

```bash
sos-project/
│
├── frontend/
│
└── backend/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/MDRAJAKHAN/smart-emergency-sos-system.git
```

---

# 🚀 Backend Setup

## Go to backend folder

```bash
cd backend
```

## Install dependencies

```bash
npm install
```

## Create `.env` file

```env
MONGO_URI=mongodb://127.0.0.1:27017/sosDB
JWT_SECRET=secret
```

## Start backend server

```bash
node server.js
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 💻 Frontend Setup

## Open new terminal

```bash
cd frontend
```

## Install dependencies

```bash
npm install
```

## Start frontend

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 📦 Required Packages

## Frontend Packages

```bash
npm install axios react-router-dom socket.io-client
```

```bash
npm install -D tailwindcss postcss autoprefixer
```

---

## Backend Packages

```bash
npm install express mongoose cors dotenv bcryptjs jsonwebtoken socket.io
```

---

# 🎯 How It Works

1. User logs into the application.
2. User clicks the **SEND SOS** button.
3. Browser captures live GPS location using Geolocation API.
4. SOS alert with Google Maps link is generated.
5. Emergency alert is shared instantly with registered contacts.
6. Real-time communication handled using Socket.IO.

---

# 🔐 Authentication

- JWT-based authentication
- Secure password hashing using bcrypt.js

---

# 🌍 APIs Used

- Browser Geolocation API
- Google Maps Location Sharing

---

# 📸 Future Enhancements

- Live map dashboard
- Email/SMS notifications
- AI-based emergency detection
- Push notifications
- Mobile app integration

---

# 👨‍💻 Author

## MD RAJA KHAN

- LinkedIn: https://linkedin.com/in/md-raja-khan-6b9070226
- GitHub: https://github.com/MDRAJAKHAN

---
