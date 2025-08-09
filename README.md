
---

# 🌐 URL Shorty - A MERN Stack URL Shortener

![URL Shorty App](https://placehold.co/800x400/111827/7dd3fc?text=URL+Shorty+App)

**URL Shorty** is a full-stack URL shortening web application built with the **MERN (MongoDB, Express.js, React, Node.js)** stack. This app allows users to convert long URLs into short, easy-to-share links and tracks the number of times each link is visited.

---

## 🚀 Features

* 🔗 **Shorten URLs** — Enter a long URL and receive a unique, short link.
* 🔁 **Seamless Redirection** — Visiting a short link automatically redirects to the original URL.
* 📈 **Click Tracking** — Admin dashboard shows all shortened links with click counts.
* 🧠 **RESTful API** — Clean backend API for creating and redirecting links.
* 💻 **Modern Frontend** — Responsive UI built with **React** and styled using **Tailwind CSS**.
* 📋 **Copy to Clipboard** — Easily copy generated short URLs in one click.

---

## 🛠️ Tech Stack

### 🔧 Backend

* **Node.js** – JavaScript runtime
* **Express.js** – Server framework
* **MongoDB** – NoSQL database
* **Mongoose** – ODM for MongoDB
* **shortid** – Unique short code generator
* **cors** – Cross-Origin Resource Sharing
* **dotenv** – Environment variable management

### 🎨 Frontend

* **React** – UI library
* **React Router** – Frontend routing
* **Axios** – API requests
* **Tailwind CSS** – Utility-first CSS

---

## 📋 Prerequisites

Ensure the following are installed:

* [Node.js](https://nodejs.org/en/)
* [MongoDB](https://www.mongodb.com/try/download/community) (local or cloud instance)

---

## 🧪 Installation & Setup

Follow the steps below to run the application locally.

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/your-username/url-shorty.git
cd url-shorty
```

---

### 🔹 2. Backend Setup

Navigate to the backend directory and install dependencies:

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
# .env
MONGO_URI=mongodb://localhost:27017/url-shortener
BASE_URL=http://localhost:5000
```

Start the backend server:

```bash
node server.js
```

> 🟢 Backend is now running on: `http://localhost:5000`

---

### 🔹 3. Frontend Setup

Open a new terminal, then:

```bash
cd frontend
npm install
npm start
```

> 🟢 Frontend will launch at: `http://localhost:3000`

---

## 🌍 App URLs

* **Main App:** `http://localhost:3000`
* **Admin Page:** `http://localhost:3000/admin`

---

## 🔌 API Endpoints

| Method | Endpoint       | Description                                     |
| ------ | -------------- | ----------------------------------------------- |
| POST   | `/api/shorten` | Create a new short URL from a long URL.         |
| GET    | `/:shortcode`  | Redirect to the original URL and track the hit. |
| GET    | `/api/urls`    | Retrieve all shortened URLs (admin only).       |

---

## 📄 License

This project is **open-source**. Feel free to fork, modify, and use it as you see fit.


---
