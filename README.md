# ✨ NodeTalk – Full Stack Realtime Chat App ✨

A modern real-time chat application built with the **MERN stack**, featuring real-time messaging likw WhatsApp, user authentication, and cloud image uploads.

---

## 🌟 Features

- 🔄 Real-time messaging with **Socket.io**
- 🔐 User authentication & JWT-based authorization
- 👤 Online user presence tracking
- 🧠 Global state with **Zustand**
- 💅 Modern UI with **TailwindCSS** and **DaisyUI**
- ☁️ Image storage via **Cloudinary**
- 🛠️ Comprehensive error handling
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

| Category      | Tech Used                            |
| ------------- | ------------------------------------ |
| **Frontend**  | React.js, TailwindCSS, DaisyUI       |
| **State**     | Zustand                              |
| **Backend**   | Node.js, Express.js                  |
| **Database**  | MongoDB (Atlas)                      |
| **Real-time** | Socket.io                            |
| **Auth**      | JWT                                  |
| **Storage**   | Cloudinary                           |
| **Deploy**    | Vercel (Frontend), Render (Backend)  |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- Cloudinary account
- Git installed

---

## 🧰 Installation & Setups to Follow to run

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd NodeTalk
```

### 2️⃣ Install Dependencies

```bash
# (Optional) Install root dependencies
npm install

# 2.1: Install frontend dependencies
cd frontend
npm install

# 2.2: Install backend dependencies
cd ../backend
npm install
```

> 💡 **Downloaded ZIP instead of Git clone?** Just unzip the folder and follow the same steps.

---

### 🔐 Environment Configuration

### 3️⃣ Create a `.env` File

In the `backend` directory, create a file named `.env` and add the following:

```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

> 📝 Replace the values above with your actual credentials from MongoDB Atlas and Cloudinary.

---

## 🧪 Running the App Locally

### 4️⃣ Build the Frontend

```bash
cd frontend
npm run build
```

### 5️⃣ Start the Backend Server

```bash
cd ../backend
npm start
```

Now open your browser and go to:

```
http://localhost:5001
```

Or your hosted backend URL like:

➡️ [https://nodetalk-chat-app.onrender.com/login](https://nodetalk-chat-app.onrender.com/login)

---

## 🧪 Development Ports

- Frontend: [http://localhost:5173](http://localhost:5173)
- Backend: [http://localhost:5001](http://localhost:5001)

---

## 🔧 Deployment

- ✅ **Frontend**: Deploy on **Vercel**
- ✅ **Backend**: Deploy on **Render**

> Make sure your frontend uses the correct base URL for API requests, e.g.:
> `https://your-backend-service.onrender.com/api`

---

## 🤝 Contributing

We welcome contributions, feedback, and feature requests!

📌 To contribute:

1. Fork the repo  
2. Create a new branch  
3. Commit your changes  
4. Open a pull request  

---

## 👤 Author

- **Reddy Gopal Krishna**

---

## 🙏 Acknowledgments

- [Socket.io](https://socket.io)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Cloudinary](https://cloudinary.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
