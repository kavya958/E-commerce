
# 🛍️ E-commerce Frontend

This is the **React-based frontend** for the E-commerce Order Management System, developed by **Kavya Chellem** as part of an official office assignment.

---

## 🚀 Overview

- View all customer orders  
- Apply filters based on Order ID, Customer, Item, Date, Pricing, and Status  
- Pagination and tab-based order filtering  
- Data dynamically fetched from Spring Boot backend

---

## 🛠️ Technologies Used

- React (Vite)  
- Axios  
- Bootstrap  
- JavaScript

---

## 📁 Folder Structure

```
ecom-frontend/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   └── OrderDashboard.jsx
├── package.json
└── vite.config.js
```

---

## ⚙️ Setup Instructions

### 1. Clone the repo:
```bash
git clone https://github.com/kavya958/E-commerce-frontend.git
cd ecom-frontend
```

### 2. Install dependencies:
```bash
npm install
```

### 3. Start the dev server:
```bash
npm run dev
```

> Frontend will run at: `http://localhost:5173/`

---

## 🔗 Backend Dependency

Ensure the Spring Boot backend is running at: `http://localhost:8080`

API used by frontend:
```
GET /api/orders
```

---

## 🔍 Features

- Tabbed filters: All, Completed, Canceled, etc.  
- Filter by Order ID, Customer, Item, Date range, Price range, Status  
- Pagination (10 orders per page)  
- Bootstrap styled responsive layout

---

## 💻 Screenshot

_(Include screenshot of Order Dashboard with filters and table display here)_

---

## 👩‍💻 Author

**Kavya Chellem**  
This frontend is built for internal office use only.
