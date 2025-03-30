
# 🚗 Car Rental System

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that allows authenticated users to manage car rentals through CRUD operations on Cars, Customers, and Rentals. Built for IFN636 - Software Life Cycle Management at QUT.

## 🔧 Features

- ✅ User Registration & Login (JWT-based)
- ✅ Authentication & Protected Routes
- ✅ CRUD Operations for:
  - Cars
  - Customers
  - Rentals (with start date, end date, price/day)
- ✅ Bootstrap UI with modals for editing
- ✅ Axios for seamless frontend-backend communication
- ✅ MongoDB Atlas cloud database
- ✅ GitHub Actions CI/CD with AWS EC2 deployment
- ✅ Project tracking with Jira and version control via Git branching

## 🛠️ Tech Stack

| Layer        | Technology                    |
|-------------|-------------------------------|
| Frontend     | React.js, Bootstrap, Axios    |
| Backend      | Node.js, Express.js           |
| Database     | MongoDB Atlas + Mongoose      |
| Auth         | JWT, React Context            |
| DevOps       | GitHub Actions, PM2, EC2      |
| Project Mgmt | Jira, GitHub, Draw.io (SysML) |

## 🚀 Getting Started

### 🔑 Prerequisites

- Node.js (v16+)
- MongoDB Atlas connection URI
- Git

### 🔄 Installation

```bash
# Clone the repository
git clone https://github.com/aniketkhot/car-rental-system
cd car-rental-system

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 🔐 Setup Environment Variables

Create a `.env` file inside the `backend` folder:

```env
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=5001
```

### ▶️ Run the App (Dev Mode)

```bash
# From root directory
npm run dev
```

This starts both frontend (http://localhost:3000) and backend (http://localhost:5001).

## 📦 Folder Structure

```
car-rental-system/
├── backend/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── App.js
│   │   └── index.js
└── README.md
```

## ⚙️ Deployment (CI/CD)

- GitHub Actions configured to run tests and deploy on push to `main`
- EC2 Instance hosted on AWS
- PM2 used for process management
- YAML workflow handles build, test, and SSH-based deployment

## 📌 Screenshots

> Include screenshots of your UI, modals, and protected routes here for visual clarity (optional for submission)

## 📘 Documentation

- SysML Requirement Diagram (`/docs/sysml_requirement_diagram.drawio`)
- Jira Board (link + screenshots)
- CI/CD Workflow YAML file in `.github/workflows/`

## 👨‍🎓 Developed For

**QUT - IFN636 Software Life Cycle Management**  
Semester 1, 2025

## ✅ Author

- [Aniket Khot](https://github.com/aniketkhot)

## 📄 License

This project is part of academic coursework and not licensed for commercial use.
