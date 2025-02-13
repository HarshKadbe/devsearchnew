# 🔍 DevSearch - Developer Portfolio Showcase

## 📌 Overview

DevSearch is a web application built with **Django** that allows developers to showcase their projects, connect with others, and collaborate. It features an interactive frontend and a backend powered by **Django ORM and SQLite**.

## 🚀 Features

✅ **User Authentication** - Sign up, log in, and manage your profile 🔑  
✅ **Developer Profiles** - Create and edit developer profiles 📄  
✅ **Project Showcase** - Upload and display projects with descriptions 🚀  
✅ **Search & Filter** - Find developers by skills and expertise 🔍  
✅ **Messaging System** - Connect with other developers via messages 📩  
✅ **Responsive UI** - Fully optimized for mobile and desktop devices 📱

## 🏗️ Tech Stack

- **Backend:** Django 🐍
- **Frontend:** HTML, CSS, JavaScript 🎨
- **Database:** SQLite 🗄️
- **Authentication:** Django's built-in auth system 🔒

## 📂 Project Structure

```
📦 devsearchnew-master
├── 📄 manage.py
├── 📄 requirements.txt
├── 📄 db.sqlite3
├── 📂 Dev Frontend
│   ├── 📄 login.html
│   ├── 📄 login.js
│   ├── 📄 main.css
│   ├── 📄 main.js
│   ├── 📄 projects-list.html
├── 📂 devsearch
│   ├── 📄 settings.py
│   ├── 📄 urls.py
│   ├── 📄 models.py
│   ├── 📄 views.py
│   ├── 📂 templates (Django templates)
│   ├── 📂 static (CSS, JS, Images)
└── 📄 README.md
```

## 🔧 Installation

1️⃣ **Clone the repository**

```bash
git clone https://github.com/HarshKadbe/devsearch.git
cd devsearchnew-master
```

2️⃣ **Create a virtual environment** (Optional but recommended)

```bash
python -m venv env
source env/bin/activate  # For Linux/macOS
env\Scripts\activate    # For Windows
```

3️⃣ **Install dependencies**

```bash
pip install -r requirements.txt
```

4️⃣ **Run migrations**

```bash
python manage.py migrate
```

5️⃣ **Run the server**

```bash
python manage.py runserver
```

6️⃣ **Open the app in browser**

```
http://127.0.0.1:8000/
```

## 📜 License

This project is **MIT Licensed** 📝. Feel free to use and contribute.

## 🤝 Contributing

Pull requests are welcome! 🚀 If you have suggestions, create an issue and let's discuss.
