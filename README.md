# Chat-Application

A full-stack real-time chat application built using the **MERN stack (MongoDB, Express, React, Node.js)** along with **Socket.io** for real-time communication and **JWT** for secure authentication.

## 🚀 Features

- 🔐 User Registration & Login with JWT Authentication
- 🧠 State management using Redux Toolkit
- 💬 Real-time One-to-One Chat using Socket.io
- 👤 User Search Functionality
- 🌐 RESTful API for Chat, Message & User management
- 🖼️ Profile picture support
- 🪪 Protected Routes
- 📁 MongoDB Atlas for cloud database
- ⚡ Backend: Node.js, Express.js
- 🖥️ Frontend: React + Tailwind CSS + DaisyUI
- 📦 Project structured for scalability

---

## 📁 Project Structure

```
Chat-Application/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── services/
│   └── main.jsx
```

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Chat-Application.git
cd Chat-Application
```

### 2. Setup MongoDB Atlas

1. Go to [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
2. Create a free cluster
3. Create a database user with **Read and Write to Any Database**
4. Whitelist your IP (use `0.0.0.0/0` to allow from anywhere)
5. Copy the **Node.js connection string**

Update the string like this:

```
mongodb+srv://<username>:<password>@cluster0.mongodb.net/<your-db-name>?retryWrites=true&w=majority
```

---

### 3. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_uri_here
JWT_SECRET=your_jwt_secret_here
```

Run the backend server:

```bash
npm run dev
```

---

### 4. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

Open the app in your browser at: `http://localhost:5173`

---

## 🔮 Future Improvements

- 🗨️ Group Chat support
- 📱 Mobile responsive improvements
- 🔔 Push Notifications for new messages
- ✅ Message read receipts
- 📷 Media (images, video, file) sharing
- 📦 Docker support for deployment
- 🧪 Unit & Integration Tests

---

## 📷 Demo

coming soon....

