# Social Network API

A social network backend built with Django and Django REST Framework.

This project provides APIs for user authentication, posts, comments, likes, and friendship requests.

---

## 📖 About

This project is part of my backend learning journey.
It was developed by following a Django REST Framework course, while implementing and practicing each concept throughout
the development process.

The goal of this project is to gain practical experience in building RESTful APIs using Django.

---

## ✨ Features

- User authentication
- User profiles
- Country management
- Post management
- Comments system
- Likes system
- Friendship request system

---

## 🛠 Technologies

- Python 3
- Django
- Django REST Framework (DRF)
- Simple JWT Authentication
- MySQL
- Git
- GitHub

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/saeedfr20/social_network.git
```

### 2. Move into the project directory

```bash
cd social_network
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

Choose the command based on your operating system:

**Windows**

```bash
.\.venv\Scripts\Activate.ps1
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure local settings

Copy the example file:

```text
social_network/local_settings.py.example
```

Rename it to:

```text
social_network/local_settings.py
```

Then update the database credentials and other local settings according to your local environment.

### 7. Apply database migrations

```bash
python manage.py migrate
```

### 8. Run the development server

```bash
python manage.py runserver
```

---

## ✅ Implemented Features

### 👤 Accounts

- ✅ User authentication with JWT (Simple JWT)
- ✅ User profile management
- ✅ Country model
- ✅ Device management
- ✅ Customized Django Admin

### 📝 Posts

- ✅ Create posts
- ✅ Update posts
- ✅ Delete posts
- ✅ Upload files for posts
- ✅ Comment system
- ✅ Like system

### 🤝 Friendship

- ✅ Send friendship requests
- ✅ Accept friendship requests
- ✅ Friend list
- ✅ User search

---

## 🎯 Learning Goals

This project helped me learn:

- Django
- Django REST Framework
- JWT Authentication
- MySQL Integration
- REST API Design
- Git & GitHub
- Django project structure
