<h1 align="center">💬 ChillChat – Real-Time Full-Stack Chat Application</h1>

<p align="center">
A secure, scalable and modern real-time messaging platform built using the MERN stack.
</p>

<p align="center">
  <a href="https://chillchat-0gr2.onrender.com/"><strong>🔗 Live Demo</strong></a>
</p>

---

## 🚀 Overview

ChillChat is a production-ready real-time chat application that enables instant communication with secure authentication, online presence tracking, media sharing, and email notifications.

This project focuses on building real-world backend architecture, WebSocket-based communication, and scalable full-stack systems rather than just basic CRUD functionality.

It demonstrates how modern messaging platforms are designed using secure APIs, real-time sockets, and cloud integrations.

---

## ✨ Features

- 🔐 Custom JWT Authentication (No third-party auth services)
- ⚡ Real-time messaging with Socket.io
- 🟢 Online / Offline presence indicators
- 🔔 Typing sounds & notification alerts (toggle support)
- 📨 Automated welcome emails on signup
- 🗂️ Image uploads with Cloudinary
- 🚦 API rate limiting for enhanced security
- 🎨 Clean, responsive and modern UI
- 🧠 Global state management with Zustand
- 🧰 RESTful backend architecture
- 🚀 Easy deployment (Render compatible)

---

## 🛠 Tech Stack

### Frontend
- React.js
- JavaScript
- Tailwind CSS
- DaisyUI
- Zustand

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Real-Time Communication
- Socket.io (WebSockets)

### Integrations & Services
- JWT Authentication
- Resend (Emails)
- Cloudinary (Image Storage)
- Arcjet (Rate Limiting & Security)

### Deployment
- Render

---

## 📂 Project Structure

```
ChillChat/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── store/
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the backend folder and add:

```
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

---

## 🧑‍💻 Local Setup & Installation

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/chillchat.git
cd chillchat
```

### 2️⃣ Install Backend Dependencies

```
cd backend
npm install
npm run dev
```

### 3️⃣ Install Frontend Dependencies

Open a new terminal:

```
cd frontend
npm install
npm run dev
```

Frontend runs on:
```
http://localhost:5173
```

Backend runs on:
```
http://localhost:3000
```

---

## 📸 Screenshots

Add your screenshots inside:

```
/frontend/public/
```

Example:

```
![App Screenshot](frontend/public/screenshot-for-readme.png)
```

---

## 🧠 Key Learnings

- Building real-time systems using WebSockets
- Designing secure JWT authentication
- Structuring scalable REST APIs
- Cloud-based media storage handling
- Rate limiting and backend protection
- State management with Zustand
- Production deployment workflows

---

## 🚀 Future Improvements

- Group chats
- Message reactions
- File & document sharing
- Push notifications
- Dark/Light mode toggle
- Docker support
- Read receipts

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push branch
5. Open Pull Request

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Rakesh Kushwaha 
Full Stack MERN Developer  
Feel free to connect and collaborate 🚀
