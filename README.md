# ConvoCloud

ConvoCloud is a simple project designed to help you understand and implement the basics of web deployment, version control, and collaborative coding. This repository can be used as a foundation to build, deploy, and manage web applications.

## Features

* Basic project setup for deployment
* Easy to extend and customize
* Beginner-friendly structure

## 📂 Project Structure

```
project-root/
│
├─ backend/
│ ├─ src/
│ │ ├─ index.js # Entry point for backend (Express server)
│ │ ├─ routes/ # API routes
│ │ │ ├─ auth.routes.js
│ │ │ ├─ user.routes.js
│ │ │ └─ message.routes.js
│ │ ├─ controllers/ # Route handlers
│ │ │ ├─ auth.controller.js
│ │ │ ├─ user.controller.js
│ │ │ └─ message.controller.js
│ │ ├─ models/ # Mongoose models
│ │ │ ├─ user.model.js
│ │ │ └─ message.model.js
│ │ ├─ middlewares/ # Middleware (auth, error handling)
│ │ └─ utils/ # Helpers (e.g., token generation)
│ └─ package.json
│
├─ frontend/
│ ├─ src/
│ │ ├─ components/
│ │ │ ├─ ChatWindow.jsx
│ │ │ ├─ Sidebar.jsx
│ │ │ └─ Message.jsx
│ │ ├─ contexts/
│ │ │ └─ ThemeContext.jsx
│ │ ├─ pages/
│ │ │ ├─ Login.jsx
│ │ │ ├─ Register.jsx
│ │ │ └─ PeerForum.jsx
│ │ ├─ App.jsx
│ │ └─ index.js
│ └─ package.json
│
└─ .env
```

* **Root Directory**: The top-level folder of the repository (`ConvoCloud/`). Use this when deploying to platforms like Render.

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sakshamkumarsingh11/ConvoCloud.git
cd ConvoCloud
```

## Tech Stack

- **Frontend**: React, Context API, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Real-time Communication**: Socket.IO (optional)
- **Authentication**: JWT

---

## 2 Installation

### Backend

```bash
cd backend
npm install


## 🌐 Deployment

* When deploying to **Render**, set the **Root Directory** to `.` (the current folder), unless your app code is inside a subfolder.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. Contributions, issues, and feature requests are welcome!
