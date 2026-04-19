# 🚀 Agile Track System

## 📖 Project Overview

The **React Agile Track System** is a Single Page Application (SPA) developed as part of my **Wipro Training Program under Techademy**.

This application helps teams efficiently manage agile workflows by enabling task tracking, team collaboration, and administrative control.

### 🔹 Key Objectives

* Streamline task management in Agile/Scrum environments
* Provide role-based access for Admins and Employees
* Enable real-time tracking of task progress

---

## ✨ Features

* 🔐 **User Authentication** (Login & Signup)
* 👥 **Role-Based Access Control** (Admin & Employee)
* 📊 **Scrum Team Management**
* 📌 **Task Assignment & Tracking**
* 🔄 **Task Status Updates** (To Do, In Progress, Done)
* 🛠️ **Admin Controls**

  * Add/Manage Users
  * Assign Tasks
  * Update Task Status
* 👤 **User Profile & Task History**
* 📱 **Responsive UI using Bootstrap**
* 🌐 **JSON Server as Fake REST API**

---

## 📂 Folder Structure

```
react-agile-track-system/
│── public/                       # Static files  
│── src/  
│   ├── components/  
│   │   ├── Dashboard/
│   │   │   └── Dashboard.js      # Displays Scrum Teams  
│   │   ├── Login/
│   │   │   └── Login.js          # Login Page  
│   │   ├── Signup/
│   │   │   └── SignUp.js         # User Registration  
│   │   ├── ScrumDetails/
│   │   │   └── ScrumDetails.js   # Tasks & Users in Scrum  
│   │   ├── UserProfile/
│   │   │   └── UserProfile.js    # User Task History  
│   ├── context/  
│   │   └── UserContext.js        # Global Auth State  
│   ├── App.js                    # Main Component  
│   ├── index.js                  # Entry Point  
│── db.json                       # Fake Backend Data  
│── package.json                  # Dependencies  
│── README.md                     # Documentation  
```

---

## ⚡ Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/react-agile-track-system.git
cd react-agile-track-system
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start JSON Server (Backend)

```bash
npm run json-start
```

🔹 Runs at: **[http://localhost:4000](http://localhost:4000)**

### 4️⃣ Start React App

```bash
npm start
```

🔹 Runs at: **[http://localhost:3000](http://localhost:3000)**

---

## 📌 User Roles & Permissions

| Role         | Permissions                                   |
| ------------ | --------------------------------------------- |
| **Admin**    | Add/Manage Users, Assign Tasks, Update Status |
| **Employee** | View Tasks, Track Progress                    |

---

## 🛠️ Tech Stack

* **Frontend:** React.js
* **State Management:** Context API
* **Styling:** Bootstrap
* **Backend (Mock):** JSON Server
* **Tools:** Node.js, npm

---

## 🤝 Contribution Guidelines

Contributions are welcome!

1. Fork the repository
2. Create a new branch

   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes

   ```bash
   git commit -m "Added new feature"
   ```
4. Push to GitHub

   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request

---

## 📬 Contact

For any queries or suggestions, feel free to reach out:

📧 **[satyam.kumar1183@gmail.com](mailto:satyam.kumar1183@gmail.com)**

---
