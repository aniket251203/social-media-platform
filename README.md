# 📘 Project Name: Mini Social Media Platform

## ✅ TASK 2: Social Media Platform

This project is a mini social media web application that allows users to create profiles, share posts, comment, and follow each other. It simulates a basic version of a social networking platform using full-stack web technologies.

---

## 📌 Project Overview

The goal of this task is to develop a simple social media platform with basic interactive features, including profile management, post creation, commenting, and a like/follow system. This project helps understand user interaction, data modeling, and CRUD operations in full-stack development.

---

## ✨ Features

- 👤 **User Profiles** – Each user has a personal profile page.
- 📝 **Posts & Comments** – Users can share posts and comment on others' content.
- 🤝 **Like / Follow System** – Users can like posts and follow/unfollow other users.

---

## 🛠 Tech Stack

### Frontend:
- **HTML**
- **CSS**
- **JavaScript**

### Backend:
- **Django** (Python)  
  *or*  
- **Express.js** (Node.js)

### Database:
- Data models for:
  - `User`
  - `Post`
  - `Comment`
  - `Follower`

---

## 🚀 Installation Guide

1. **Clone the repository:**

```bash
git clone https://github.com/aniket251203/social-media-platform.git
cd social-media-platform

2. (For Django) Create a virtual environment and install dependencies:
python -m venv venv
source venv/bin/activate       # For Linux/macOS
venv\Scripts\activate          # For Windows
pip install -r requirements.txt

3.Run migrations and start the server:

python manage.py makemigrations
python manage.py migrate
python manage.py runserver
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Folder Structure
social-media-platform/
│
├── social_app/           # Django app (or Express.js app if used)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── static/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
