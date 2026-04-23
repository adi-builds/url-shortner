# 🔗 URL Shortener

A simple full-stack URL shortener built with React and Express.
It allows users to convert long URLs into short, shareable links.

---

## 🚧 Project Status

**In Progress**

* ✅ Backend (API & database) completed
* ⚙️ Frontend partially built
* ❌ UI/UX improvements pending
* ❌ Deployment not done yet

---

## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS
* DaisyUI

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Other Tools

* NanoID (for generating short IDs)
* CORS
* Nodemon

---

## ⚙️ Features

* 🔗 Generate short URLs from long links
* 📦 Store URLs in database
* 🚀 Fast API responses
* 🎨 Basic frontend UI (work in progress)

---

## 📁 Folder Structure

```
url-shortener/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── .env (ignored)
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── App.jsx
│
└── README.md
```

---

## 🔑 Environment Variables

Create a `.env` file in the backend folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:5000
```

⚠️ Do NOT upload your `.env` file to GitHub.

---

## ▶️ Getting Started

### 1. Clone the repository

```
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
```

### 2. Install backend dependencies

```
cd backend
npm install
```

### 3. Run backend server

```
npm run dev
```

### 4. Install frontend dependencies

```
cd ../frontend
npm install
```

### 5. Run frontend

```
npm run dev
```

---

## 📌 Future Improvements

* Add analytics (click tracking)
* Improve UI/UX
* Add custom short URLs
* Authentication system
* Deploy on cloud (Vercel + Render)

---

## 🤝 Contributing

This is a personal learning project, but suggestions and improvements are welcome.

---

## 📜 License

This project is open-source and free to use.

---
