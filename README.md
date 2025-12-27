markdown
# GearGuard - Smart Maintenance Management System

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0-green?style=for-the-badge&logo=flask)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

**GearGuard** is a production-grade **Computerized Maintenance Management System (CMMS)** built to streamline equipment repairs, preventive maintenance, and asset lifecycle tracking.  
It features intelligent conflict prevention, warranty protection logic, role-based dashboards, and visual workflow management.

---

## 🚀 Key Features

### 🧠 Smart Intelligence
- **Duplicate Ticket Prevention**
- **Warranty Protection Logic**

### 👤 User Experience
- **Role-Based Access Control**
- **OAuth Social Login (Google & GitHub)**
- **Modern Glassmorphism UI**

### 🛠️ Admin Power Tools
- **Kanban Workboard**
- **Visual Scheduler**
- **Analytics Dashboard**
- **CSV Data Export**

---

🛠️ Tech Stack

- **Backend:** Python, Flask, SQLAlchemy, Flask-Login, Authlib  
- **Frontend:** HTML5, CSS, Bootstrap 5, JavaScript , Jinja2
- **Database:** SQLite (Dev) / PostgreSQL (Prod)  
- **Charts & Scheduling:** Chart.js, FullCalendar  

---


## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/GearGuard.git
cd GearGuard
````

### 2️⃣ Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Initialize Database

```bash
python reset_db.py
```

### 5️⃣ Run Application

```bash
python app.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## 📂 Project Structure

```
GearGuard/
├── app.py                 # Main controller & routes
├── config.py              # Configuration settings
├── reset_db.py            # Database initialization
├── requirements.txt       # Python dependencies
│
├── models/
│   ├── db.py
│   ├── user.py
│   ├── equipment.py
│   └── request.py
│
├── static/
│   ├── css/
│   └── uploads/
│
└── templates/
    ├── auth/
    ├── layouts/
    ├── requests/
    ├── equipment/
    ├── dashboard_admin.html
```

---

## 🧾 License

This project is licensed under the **MIT License**.


