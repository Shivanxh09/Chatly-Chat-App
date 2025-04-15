# Chatly - Real-Time Chat App 💬

Chatly is a real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js) with Socket.IO integration. It allows users to sign up, log in, chat in real-time, and enjoy a modern chat experience.

## 🚀 Features

- 🔐 User Authentication (JWT-based)
- 🧑‍🤝‍🧑 One-on-One and Group Chats
- 🔔 Real-time Messaging with Socket.IO
- 📱 Responsive UI (Mobile Friendly)
- ✉️ Notifications for New Messages
- 🖼️ User Avatars & Chat Management

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS, Axios, React Router
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, Socket.IO
- **Authentication:** JWT, bcrypt
- **Other Tools:** Postman, MongoDB Atlas


## 📂 Folder Structure
```
Chatly-Chat-App/
│
├── frontend/            # React Frontend
│   ├── public/          # Static files
│   └── src/             # Source files
|       ├── assets/      # Images, logos, and static assets
│       ├── components/  # Reusable UI components
│       ├── pages/       # Main page components
│       └── context/     # React Context for global state
│
├── backend/             # Node.js Backend
│   ├── config/            # DB and server config
│   ├── controllers/       # Business logic
│   ├── middleware/        # Custom middleware
│   ├── models/            # Mongoose schemas/models
│   └── routes/            # Express routes
└── README.md              # Project documentation  

```
## ⚙️ Getting Started

### Prerequisites

- Node.js & npm
- MongoDB Atlas or local MongoDB setup

### Installation

1. **Clone the repository**
```
git clone https://github.com/Shivanxh09/Chatly-Chat-App.git
cd Chatly-Chat-App
```
2. **Install dependencies for frontend and backend**

```
cd frontend
npm install
cd ../backend
npm install
```
3. **Set up environment variables**
   Create a .env file in the backend/ directory:
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```
4. **Run the app**
   Backend

```
cd backend
npm start
```
  Frontend
```
cd frontend
npm start
```
## ✅ To-Do
- Add emoji support

- Implement typing indicators

- Add dark mode

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📧 Contact
Made by Shivanxh09 – feel free to reach out!
