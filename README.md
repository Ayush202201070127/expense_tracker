# Expense Tracker SQL

A full-stack Expense Tracker web application built using Node.js, Express.js, MySQL, and Sequelize ORM. The application helps users manage daily expenses, track spending habits, and view expense reports efficiently.

---

## 🚀 Features

- User Authentication (Signup/Login)
- JWT-based Authorization
- Add, Edit, and Delete Expenses
- Expense Categorization
- Leaderboard for Premium Users
- Download Expense Reports
- Razorpay Payment Integration
- Password Reset using Brevo Email Service
- Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- Bootstrap
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL
- Sequelize ORM

### Other Services
- JWT Authentication
- Razorpay Payment Gateway
- Brevo Email API

---

## 📂 Project Structure

```bash
Expense_Tracker_SQL/
│
├── controllers/
├── middleware/
├── models/
├── public/
│   ├── css/
│   ├── js/
│   └── views/
├── router/
├── util/
├── app.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/Ayush202201070127/expense_tracker.git
```

```bash
cd expense_tracker
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Create MySQL Database

```sql
CREATE DATABASE expense_tracker;
```

---

### 4. Configure Environment Variables

Create a `.env` file in the root directory.

```env
PORT=3000

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_SCHEMA=expense_tracker

SECRET_KEY=your_secret_key

BREVO_API_KEY=your_brevo_api_key

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```

---

### 5. Start Application

```bash
npm start
```

---

## 🌐 Application URL

```text
http://localhost:3000
```

---

## 📸 Screenshots

### User Dashboard
- Add and manage expenses
- View reports and premium features

### Leaderboard
- Displays premium users ranked by total expenses

---

## 🔐 Authentication

- Passwords are encrypted using bcrypt
- JWT tokens used for session management

---

## 💳 Premium Features

- Expense Leaderboard
- Download Reports
- Advanced Expense Tracking

---

## 📦 Deployment

This project can be deployed using:

- Render (Backend)
- Railway (MySQL Database)
- Netlify/Render (Frontend)

---

## 📄 License

This project is licensed under the MIT License.
