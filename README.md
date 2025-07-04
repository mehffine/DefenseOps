# 🛡️ DRDO ER/IPR Portal – Frontend

This is the **frontend** of the secure DRDO ER/IPR web portal. It allows authenticated users to submit new project entries and manage previously submitted records through a clean, modern UI built with **React** and **Tailwind CSS**.

---

## 🚀 Features

* 📝 **Data Entry Form** — Submit new ER/IPR project records
* 📊 **Dashboard** — View, filter, and manage submitted records
* 🔐 **Login Authentication** — Secure login screen
* 🧭 **Navigation** — Navbar and footer for seamless routing
* 🎨 **Consistent UI** — DRDO-themed styling with Tailwind CSS

---

## 📁 File Structure

```
DRDO-Frontend/
├── public/
│   └── index.html
├── src/
│   ├── assets/         # Images (logo, banner, etc.)
│   ├── components/     # Reusable UI components (Navbar, Footer)
│   ├── pages/          # React pages (Home, Login, Form, Dashboard)
│   ├── App.jsx
│   ├── index.js
│   └── tailwind.config.js
├── .gitignore
├── package.json
└── vite.config.js
```

---

## 📦 Installation

```bash
cd DRDO-Frontend
npm install
```

---

## 🧪 Running the App Locally

```bash
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🌐 Pages Overview

| Page      | Route        | Description                           |
| --------- | ------------ | ------------------------------------- |
| Login     | `/`          | Secure login with username/password   |
| Home      | `/home`      | Welcome screen with navigation        |
| Form      | `/form`      | Data entry for ER/IPR records         |
| Dashboard | `/dashboard` | View and update all submitted records |

---

## 🔧 Tech Stack

* ⚛️ **React**
* 🧭 **React Router DOM**
* 💨 **Tailwind CSS**
* ⚡ **Vite**

---

## 📌 Notes

* Ensure the backend is running at:
  `http://localhost:5000`
* CORS must be enabled in the backend using [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/)

---
