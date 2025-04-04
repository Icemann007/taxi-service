# 🚖 Taxi Service

A simple Django-based taxi service application.

---

## 🔧 Installation

> Make sure you have **Python 3** installed.

```bash
git clone https://github.com/Icemann007/taxi-service.git
cd taxi-service
python -m venv venv
venv/Scripts/activate       # For Windows
# or
source venv/bin/activate    # For Mac/Linux

pip install -r requirements.txt
```

## 🗄 Database Setup

Run the following commands to apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 👤 Superuser Access (Optional)

To create a superuser:

```bash
python manage.py createsuperuser
```

---

## 🚀 Run the Server

```bash
python manage.py runserver
```

---

## ✨ Features

- ✅ User registration and authentication  
- ✅ Driver and car management
- ✅ Search and filtering for drivers and cars  


---

## 📂 Demo Login

```text
Login: admin.user  
Password: admin12345
