# 🚀 Convo: Real-Time Chat Application

Welcome to **Convo**, a modern chat platform built for seamless, real-time conversations.  
This project leverages a powerful tech stack to deliver instant messaging, user presence, and a polished UI.

---

## 🛠️ Tech Stack

- **Frontend:** React, TailwindCSS, DaisyUI  
- **Backend:** Node.js, Express, MongoDB (MERN)  
- **Realtime:** Socket.io  
- **State Management:** Zustand  
- **Authentication:** JWT  
- **Media:** Cloudinary

---

## 🔒 Features

- Secure sign-up and login with JWT-based authentication
- Live chat with instant message delivery
- See who’s online in real time
- User profile management and settings
- Robust error handling on both client and server
- Effortless deployment (instructions included!)

---

## ⚙️ Getting Started

### 1. Environment Setup

Create a `.env` file in your root directory and add:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

NODE_ENV=development
```

---

### 2. Build & Run

**Build the frontend:**
```bash
npm run build
```

**Start the server:**
```bash
npm start
```

---

## 🤝 Contributing

Pull requests and suggestions are welcome.  
Let’s make Convo even better together!

---

## 📄 License

This project is open source and available under