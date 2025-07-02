# Brand Pilot Backend

🚀 **Brand Pilot** is a backend service for automating social media content generation using the AML API, built with **Node.js**, **Express**, and **MongoDB** with JWT authentication.

---

## 🚀 Features

* User authentication with JWT.
* MongoDB for storing users and generated content.
* AML API integration for generating automated content.
* Lightweight system monitoring during content generation.

---

## ⚙️ Tech Stack

* Node.js + Express
* MongoDB (Mongoose)
* JWT for authentication

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/brand-pilot-backend.git
cd brand-pilot-backend
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file in the root directory with the following:

```env
PORT=4000
MONGO_URI=
SECRET=
```

### 4️⃣ Run the Server

Run the backend using **nodemon** for auto-reloading during development:

```bash
nodemon index.js
```

The server will start on `http://localhost:4000` (or your specified `PORT`).

---

## ✅ Endpoints (Basic)

* `POST /api/auth/register` – Register a new user.
* `POST /api/auth/login` – User login and receive JWT.
* `POST /api/content/generate` – Generate content using AML API (protected).

---

## 🛠️ Notes

* Ensure **MongoDB Atlas** access is enabled for your IP.
* AML API credentials should be securely managed for live environments.
* For production, add CORS, validation, and error-handling middleware.

---

## 🚀 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss.


---

Happy building 🚀

