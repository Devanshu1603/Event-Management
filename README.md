# 📅 Planova - Event Management Platform

**Planova** is a full-stack Event Management Platform designed to streamline the process of event creation, registration, tracking, and management for both users and administrators. Built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js), it delivers a seamless, secure, and efficient event experience.

---

## 🚀 Features

✅ **User Registration & Event Participation** – Browse, register, and attend events with real-time tracking.  
✅ **Admin Dashboard** – Create, update, and monitor event participation effortlessly.  
✅ **Secure Authentication & Role-Based Access** – Ensures restricted access for users and admins.  
✅ **Real-Time Event Tracking** – Live updates on registrations and attendance.  
✅ **QR-Based Check-Ins** – Streamlines entry using QR codes for quick and secure verification.  
✅ **Responsive & Modern UI** – Built with React.js, Bootstrap, and Lucide React Icons.  
✅ **Future Enhancements** – AI-based event recommendations, ticketing & payments, social media integration.

---

## 🧰 Tech Stack

### Frontend
- React.js
- Bootstrap 5
- React Router
- Axios
- Lucide React Icons

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Tokens (JWT)
- Multer (for file uploads, if needed)

---

## 📁 Folder Structure

```
event-management/
├── frontend/      # React.js client
└── backend/       # Node.js + Express server
```

---

## 🛠️ Getting Started

### ⚙️ Prerequisites
- Node.js & npm
- MongoDB (local or MongoDB Atlas)
- Git

---

### 📥 1. Clone the Repository

```bash
git clone https://github.com/your-username/event-management.git
cd event-management
```

---

### 🔧 2. Backend Setup

```bash
cd backend
npm install
```

- Create a `.env` file in the `backend` folder:

```env
PORT=5000
MONGO_URI=your_mongo_db_connection
JWT_SECRET=your_jwt_secret
```

- Start the backend:

```bash
npm start
```

---

### 💻 3. Frontend Setup

```bash
cd ../frontend
npm install
```

- Create a `.env` file in the `frontend` folder:

```env
REACT_APP_BACKEND_URL=http://localhost:5000
```

- Start the frontend:

```bash
npm start
```

---

## 🔐 Roles

### 🧑 User:
- Sign up & login
- Explore and attend events
- Receive real-time updates
- Check-in using QR code

### 🛡️ Admin:
- Login using assigned credentials
- Create & manage events
- View all attendees and stats
- Track live event participation

---

## 📌 Upcoming Features

- 🧠 AI-based event recommendations
- 💳 Integrated ticketing & payments
- 📣 Social media sharing and invites
- 📊 Analytics dashboard

---

## 🤝 Contributing

We welcome contributions! Feel free to fork this repository, raise issues, and submit pull requests to improve the platform.

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Made with ❤️ using MERN Stack
