# 🚀 TweetApp – Django Based Microblogging Web Application

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-Framework-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

TweetApp is a Django-powered microblogging web application that allows users to create, update, and delete tweets.

The project demonstrates core backend development concepts including full CRUD functionality, Django ORM integration, form handling, template rendering, and structured project architecture.

It follows Django’s **MVT (Model-View-Template)** pattern and includes proper static and media file management.

---

## 📌 Description

This application showcases how to build a structured Django project with:

- Clean project architecture  
- Organized templates and static files  
- Database operations using Django ORM  
- Form validation using Django Forms  
- Modular app-based structure  

It is designed as a foundational backend project for learning Django web development.

---

## ✨ Features

- Create new tweets  
- Edit existing tweets  
- Delete tweets  
- View list of all tweets  
- Form validation using Django Forms  
- Django ORM for database operations  
- Structured templates and static file management  

---

## 🛠 Tech Stack

- Python  
- Django  
- SQLite  
- HTML  
- CSS  

---

## 🏗 Project Architecture

This project follows Django’s **MVT architecture**:

- **Models** – Define database schema using Django ORM  
- **Views** – Handle business logic and request/response flow  
- **Templates** – Render dynamic frontend content  

---

## 📂 Project Structure

```
TweetApp/
 ├── manage.py
 ├── requirements.txt
 ├── README.md
 ├── tweet/              # Main App
 │    ├── models.py
 │    ├── views.py
 │    ├── forms.py
 │    ├── urls.py
 │    └── migrations/
 ├── tweetapp/           # Project Configuration
 │    ├── settings.py
 │    ├── urls.py
 │    └── wsgi.py
 ├── templates/
 └── static/
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/TweetApp.git
```

### 2️⃣ Navigate to project directory

```
cd TweetApp
```

### 3️⃣ Create virtual environment

```
python -m venv venv
```

### 4️⃣ Activate virtual environment

Windows:
```
venv\Scripts\activate
```

Mac/Linux:
```
source venv/bin/activate
```

### 5️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 6️⃣ Apply migrations

```
python manage.py migrate
```

### 7️⃣ Run development server

```
python manage.py runserver
```

---

## 📚 Learning Outcomes

- Implemented full CRUD operations in Django  
- Understood Django project structure and app modularity  
- Worked with Django ORM and Models  
- Managed static and media files  
- Applied form validation and template rendering  
- Followed clean backend project structuring practices  

---

## 🔮 Future Improvements

- User authentication system  
- REST API version using Django REST Framework (DRF)  
- Like and comment functionality  
- Deployment to cloud platform (Render / Railway)  

---

## 👨‍💻 Author

**Omkar Shenwai**  
Backend Developer (Python | Django) 