# 📝 Todo Flask App

A simple and functional **To-Do List Web Application** built using **Flask** and **SQLAlchemy**, designed to help users manage their daily tasks with ease.

---

## 🚀 Features

- Add, edit, and delete todo items.
- Track tasks with timestamps.
- Persistent data using **SQLite**.
- Clean and minimal UI with **HTML/CSS + Jinja2 templating**.
- Lightweight and fast – perfect for beginners to learn Flask basics.

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask, SQLAlchemy  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, Bootstrap (optional)  
- **Templating:** Jinja2  

---

## 📦 Setup Instructions

### 1. Clone the Repository
```
git clone https://github.com/chiragtaluja/Todo-FlaskApp.git
cd Todo-FlaskApp
```
### 2. Create a Virtual Environment
```
python -m venv env
# On Windows:
env\Scripts\activate
# On macOS/Linux:
source env/bin/activate
```
### 3. Install Dependencies
```
pip install -r requirements.txt
If requirements.txt is missing, install manually:

pip install flask flask_sqlalchemy
```
### 4. Run the App
```
python app.py
The app will be available at: http://127.0.0.1:5000
```

## 🗃️ Project Structure
``` csharp
Todo-FlaskApp/
│
├── templates/
│   └── index.html
│
├── static/             # (optional for CSS/JS)
├── app.py              # Main Flask app
├── site.db             # SQLite database
└── README.md
``` 
## 📸 Screenshots

## 🙋‍♂️ Author
Chirag Taluja
🔗 [GitHub Profile](https://github.com/chiragtaluja)

## 📄 License
This project is licensed under the MIT License – feel free to use it and modify it for your own projects.