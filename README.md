# Task-Manager-Backend

This is the backend API for the **SmartTask** Task Manager web application built using **Django** and **Django REST Framework**. It powers project-based task management with productivity tracking, category-based filtering, analytics, and data export.

---

## ⚙️ Tech Stack

- Python 3.x
- Django
- Django REST Framework
- SQLite (dev) / PostgreSQL (optional)

---

## 🚀 Features

- Task CRUD operations (create, update, delete)
- Projects & Tags (color-coded categories)
- Weekly/monthly productivity metrics
- Goal tracking (daily/weekly task targets)
- Export tasks to CSV or JSON
- RESTful APIs to power React frontend

---

## 📁 Project Structure

backend/
├── manage.py
├── requirements.txt
├── .gitignore
├── backend/ # Django project
│ ├── settings.py
│ └── urls.py
└── task/ # Main app
├── models.py
├── views.py
├── serializers.py
├── urls.py
└── tests.py

## 🛠️ Setup Instructions

1. **Clone the repo**
   git clone https://github.com/yourusername/smarttask-backend.git
   cd smarttask-backend

2. **Create a virtual environment**

3. **Install dependencies**

4. **Apply migrations**
   python manage.py migrate

5. **Run the development server**
   python manage.py runserver
