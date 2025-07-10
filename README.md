# 📦 CodeAlpha Internship Tasks Submission — June Batch

This repository contains my completed tasks for the CodeAlpha June Batch internship program.

---

## 📌 Projects Included

### 🛍️ LD Shopper (E-Commerce App)

A complete **E-Commerce web application** built with a React.js frontend, Node.js & Express backend, and MongoDB database. It includes a dedicated **Admin Panel** for managing products, as well as user authentication, cart management, product filtering, and image uploads.

---

### 📦 Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose)
- **Authentication:** JSON Web Token (JWT)
- **Image Upload:** Multer
- **State Management:** React Context API

---

### 📁 Project Structure

```
E-commerce-store/
├── backend/
│   ├── index.js
│   ├── upload/
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── Components/
│   │   ├── Context/
│   │   ├── Pages/
│   │   └── App.js
│   └── package.json
├── admin/
│   ├── src/
│   │   ├── Components/
│   │   └── Pages/
│   └── package.json
└── README.md
```

---

### ⚙️ Installation & Setup

**1️⃣ Clone the Repository**

```bash
git clone https://github.com/theluchadora/codealpha_tasks.git
cd codealpha_tasks/E-commerce-store
```

**2️⃣ Install Dependencies**

**Backend:**

```bash
cd backend
npm install
```

**Frontend:**

```bash
cd ../frontend
npm install
```

**Admin Panel:**

```bash
cd ../admin
npm install
```

**3️⃣ Database Configuration**

Edit `backend/index.js` to replace:

```
mongoose.connect("mongodb+srv://<username>:<password>@cluster0.wb5aaly.mongodb.net/e-commerce");
```

with your MongoDB Atlas URI.

**⚠️ Important:**  
For production, move credentials to a `.env` file and use dotenv.

---

### 🚀 Running the Project

**Backend**

```bash
cd backend
npm start
```

Runs at `http://localhost:4000`

**Frontend**

```bash
cd frontend
npm start
```

Runs at `http://localhost:3000`

**Admin Panel**

```bash
cd admin
npm start
```

Runs at `http://localhost:5173`

---

### 📌 Features

✅ User registration & login  
✅ Cart management (Add/Remove)  
✅ Product management via Admin Panel  
✅ Image uploads for products  
✅ Category-based product filtering  
✅ New and popular product sections  
✅ Fully integrated backend & frontend  

---

## 📱 Social Media App

A **full-stack social media app** built with Node.js, Express, MongoDB, and React. Users can register, login, post images, update their profiles, like posts, and follow/unfollow other users — all through a clean and modern interface.

---

### 📂 Project Structure

```
social-media-app/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── public/
│   │   └── images/
│   │       ├── theDefaultCover.png
│   │       ├── theDefaultProfile.png
│   │       └── (other images ignored by .gitignore)
│   ├── .env (create your own as shown below)
│   ├── index.js
│   └── package.json
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

---

### 🛠️ Tech Stack

- **Frontend:** React, CSS, Axios  
- **Backend:** Node.js, Express  
- **Database:** MongoDB (with Mongoose)  
- **Authentication:** JWT  
- **Image Upload:** Multer  
- **Environment Variables:** dotenv

---

### ⚙️ Setup Instructions

**1️⃣ Clone the Repository**

```bash
git clone https://github.com/theluchadora/codealpha_tasks.git
cd codealpha_tasks/social-media-app
```

**2️⃣ Install Dependencies**

**Backend**

```bash
cd backend
npm install
```

**Frontend**

```bash
cd ../frontend
npm install
```

**3️⃣ Create `.env` File**

Inside `backend/` create a `.env` file:

```
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

**⚠️ Note:**  
Replace placeholders with your actual credentials. This file is ignored by `.gitignore`.

---

### 🚀 Running the App

**Backend**

```bash
cd backend
node index.js
```

Runs at `http://localhost:5000`

**Frontend**

```bash
cd frontend
npm start
```

Runs at `http://localhost:3000`

---

### 📦 Special Notes

- `backend/public/images/` contains `theDefaultCover.png` and `theDefaultProfile.png` for fallback profile and cover images.
- All other images are ignored via `.gitignore`.
- Ensure your `.env` is properly configured for MongoDB and JWT.

---

## ✨ Features

- User Registration & Authentication  
- Profile with image, cover photo, and bio  
- Create, edit, and delete posts  
- Like and follow/unfollow functionality  
- Clean and responsive UI  

---

## 📎 Submission Info

📌 **Main Repo:**  
https://github.com/theluchadora/codealpha_tasks

📌 **Task 1 (E-Commerce App):**  
https://github.com/theluchadora/codealpha_tasks/tree/main/E-commerce-store

📌 **Task 2 (Social Media App):**  
https://github.com/theluchadora/codealpha_tasks/tree/main/social-media-app

---

> 🔒 Both projects are organized inside this single `codealpha_tasks` repo as per CodeAlpha's submission guidelines.
