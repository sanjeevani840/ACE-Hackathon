# 🎓 Campus Buzz – The Campus Coordination Platform

> **A modern full-stack platform that simplifies campus communication, collaboration, and coordination through verified identities, real-time interaction, and role-based access control.**

Campus Buzz is a comprehensive campus coordination platform developed to solve the problem of fragmented communication across WhatsApp groups, notice boards, and word-of-mouth. The platform provides a centralized space where students, clubs, committees, and administrators can collaborate efficiently.

---

# 🚀 Problem Statement

Campus life communication is often scattered across multiple platforms, making coordination difficult for students and organizations.

Campus Buzz addresses this challenge by providing:

* 📢 A centralized campus feed
* 💬 Real-time coordination chat rooms
* 📅 Event management
* 🏛️ Official club communication
* 📝 Anonymous complaint system
* 🔐 Secure role-based authentication

---

# ✨ Core Features

## 🔐 Authentication & Role Management

* Login using Roll Number & Institute Email
* Secure JWT Authentication
* Email Verification
* Role-Based Authorization
* Protected API Routes

### Supported Roles

* 👨‍🎓 Student
* 🏛️ Club / Committee
* 👨‍💼 Admin

---

## 📢 Campus Buzz Feed

Students can create coordination posts with:

* Image
* Title
* Description
* Hashtag
* Custom Expiry Timer

Supported hashtags:

* #foodsplit
* #cabsplit
* #resell
* #lost
* #found

Features include:

* Infinite Scroll
* Search Functionality
* Hashtag Filtering
* Trending Hashtags
* Image Upload
* Countdown Timer
* Automatic Post Expiry

---

## 💬 Real-Time Collaboration

Dedicated chat rooms are automatically created for:

* #foodsplit
* #cabsplit
* #resell

Features:

* Real-time messaging
* Online user presence
* Typing indicators
* Message persistence
* Live room coordination

For **#lost** and **#found**, users can directly access the poster's contact details.

---

## 🏛️ Club & Committee Portal

A dedicated space for official communication where verified clubs and committees can:

* Publish official announcements
* Share links and images
* Embed Google Forms
* Link posts with campus events

---

## 📅 Event Calendar

A centralized calendar for campus activities.

Features:

* Create Events
* Update Events
* Delete Events
* View Upcoming Events
* Student Event Requests
* Event Approval Workflow

---

## 📝 Complaint Management System

Students can anonymously report campus-related issues.

Features:

* Anonymous complaint posting
* Secure identity storage
* Complaint status updates
* Mark complaints as resolved
* Admin moderation

---

## 🛠️ Admin Dashboard

Administrative controls for managing the platform.

Admins can manage:

* Users
* Campus Posts
* Complaints
* Events
* Reports
* Notifications

---

# ⚡ Additional Features

* Real-time communication using Socket.IO
* Infinite scrolling feed
* Search and hashtag filtering
* Trending hashtags
* Cloudinary image uploads
* Automatic post expiry using background jobs
* Countdown timer for expiring posts
* Anonymous complaint system
* Event calendar integration
* Role-based access control
* Admin moderation dashboard

---

# 🏗️ Tech Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* React Query
* Axios
* Socket.IO Client
* React Hook Form

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Socket.IO
* JWT Authentication
* Multer
* Cloudinary
* Node Cron
* Express Validator

---

# 📁 Project Structure

```
Campus-Buzz/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── sockets/
│   ├── utils/
│   ├── validations/
│   ├── cron/
│   ├── app.js
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── context/
│   │   ├── services/
│   │   ├── routes/
│   │   └── App.jsx
│   └── package.json
│
├── README.md
└── .env.example
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone <repository-url>
cd Campus-Buzz
```

---

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
```

---

# 🏛️ System Architecture

The project follows a modular MVC architecture.

* RESTful APIs
* JWT Authentication
* Role-Based Authorization
* MongoDB Database
* Socket.IO for Real-Time Communication
* Cloudinary for Image Storage
* Background Cron Jobs for Post Expiry

---

# 👥 Team

* **Palak Soni**
* **A. Sanjeevani Rao**
* **J.V.N.H. Amarnath**
* **Divya Sahu**

---

# 🌟 Future Enhancements

* Push Notifications
* Mobile Application
* AI-powered Post Recommendations
* Smart Content Moderation
* Enhanced Analytics Dashboard
* Campus Marketplace Integration

---

# 📄 License

This project was developed as part of a National Level Hackathon for educational and demonstration purposes.

---

⭐ **If you found this project interesting, consider giving the repository a star!**
