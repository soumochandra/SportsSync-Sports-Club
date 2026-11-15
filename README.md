
# 🏆 SportsSync – Sports Club Management System

**SportsSync** is a full-stack web application designed to streamline sports club operations through centralized athlete management, coach assignments, secure authentication, and administrative workflows.

## 🚀 Key Features

- **Athlete Management:** Athlete registration, profile management, and document handling.
- **Coach Management:** Coach records and athlete–coach assignments.
- **Authentication & Authorization:** Secure authentication and Role-Based Access Control (RBAC).
- **Admin Dashboard:** Centralized athlete review, approval, and management workflows.
- **RESTful APIs:** Efficient client-server communication using Node.js and Express.js.
- **Data Management:** Structured data handling and CSV export functionality.
- **Firebase Integration:** Backend data management and application services.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, JavaScript, HTML, CSS |
| Backend | Node.js, Express.js |
| Database & Services | Firebase, Firestore |
| API Architecture | RESTful APIs |
| Authentication | Secure Authentication, RBAC |
| Development Tools | Git, GitHub, VS Code |

## 🏗️ System Architecture

SportsSync follows a modular **Client–Server Architecture**, separating frontend components, backend business logic, API endpoints, and database services.

```text
        USER / ADMIN / COACH
                 |
                 ▼
          REACT.JS FRONTEND
                 |
                 ▼
          REST API REQUESTS
                 |
                 ▼
        NODE.JS + EXPRESS.JS
                 |
          ┌──────┴──────┐
          ▼             ▼
    AUTHENTICATION   BUSINESS LOGIC
          |             |
          └──────┬──────┘
                 ▼
          FIREBASE / FIRESTORE
                 |
                 ▼
          DATA MANAGEMENT
```

## 📂 Project Structure

```text
SportsSync/
├── client/                 # React.js frontend
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── services/
│       ├── hooks/
│       ├── utils/
│       ├── App.jsx
│       └── main.jsx
│
├── server/                 # Node.js backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── app.js
│   └── package.json
│
├── docs/
├── .gitignore
├── README.md
└── package.json
```

## ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/soumochandra/Phase-1-Sports-club.git
cd Phase-1-Sports-club
```

**2. Install frontend dependencies**

```bash
cd client
npm install
```

**3. Install backend dependencies**

```bash
cd ../server
npm install
```

**4. Configure Environment Variables**

Create a `.env` file and configure the required Firebase credentials and application settings.

**5. Run the application**

Start the backend and frontend in separate terminals:

```bash
# Backend
cd server
npm start
```

```bash
# Frontend
cd client
npm run dev
```

## 🔐 Security & Access Control

- Authentication and authorization mechanisms.
- Role-Based Access Control (RBAC).
- Protected administrative workflows.
- Controlled access to athlete and coach management features.

## 🎯 Project Objectives

- Digitize sports club administration.
- Reduce manual registration and record management.
- Improve athlete and coach coordination.
- Streamline approval workflows.
- Enable efficient and centralized data management.

## 👨‍💻 Developer

**Soumo Chandra**

- GitHub: [@soumochandra](https://github.com/soumochandra)
- Project: [SportsSync Repository](https://github.com/soumochandra/Phase-1-Sports-club.git)

---

⭐ If you find this project useful, consider giving it a star!
