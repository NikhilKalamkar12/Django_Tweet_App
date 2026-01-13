# 🐦 Django Tweet App

A simple **Twitter-style web application** built using **Django (Python)** that allows users to post short text updates (tweets) and view them in a feed.

This project demonstrates core Django concepts such as:
- ✔ Django setup
- ✔ Models, Views & Templates
- ✔ URL routing
- ✔ Database interaction using ORM
- ✔ Rendering HTML with dynamic content

---

## 📌 Project Description

The **Django Tweet App** is a project where users can create short text posts (tweets) and display them on a webpage. All data is managed through Django’s ORM and templates are used to render the page content dynamically.

---

## 🛠️ Tech Stack

```text
Frontend : HTML, CSS, Django Templates
Backend  : Django (Python)
Database : SQLite (default Django database)
Tools    : Django ORM – Database interactions,
           VS Code – Code editor
```

---

📂 Project Structure

The structure follows standard Django layout. It likely includes:
```text
Django_Tweet_App/
│
├── Django_Tweet_App/        # Django project configuration (settings, urls)
├── tweet/                   # Django app for tweet logic
│   ├── migrations/          # Auto-generated database migrations
│   ├── templates/           # Tweet templates
│   ├── static/              # CSS and static files
│   ├── admin.py             # Admin registrations
│   ├── models.py            # Tweet model
│   ├── views.py             # Views for showing & creating tweets
│   ├── urls.py              # App routes
│   └── forms.py             # (If used) form definitions
├── db.sqlite3               # Django SQLite database
├── manage.py                # Django management script
├── requirement.txt          # Dependencies (likely Django version)
└── README.md                # Project documentation
```

---

## ⚙️ How It Works

1. User starts the Django server
2. User visits the homepage
3. Seeing existing tweets
4. User enters tweet text in a form
5. Django saves tweets in database
6. Tweets are rendered back on page via templates

---

## ▶️ How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/NikhilKalamkar12/Django_Tweet_App.git
cd Django_Tweet_App
```

### 2️⃣ Create Python Virtual Environment
```bash
python -m venv venv
```

Activate:
- Windows
```bash
venv\Scripts\activate
```
- Mac/Linux
```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
OR 
(If that fails, you can run:
```bash
pip install django
```

### 4️⃣ Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the Development Server
```bash
cd firstone
```
```bash
python manage.py runserver
```

### 6️⃣ Open in Browser
```text
http://127.0.0.1:8000/
```
🎉 Your Django Tweet App should now be running!

---

📸 Screenshots 

#### Admin Panel
<img width="1280" height="832" alt="Screenshot 2026-01-13 at 18 39 25" src="https://github.com/user-attachments/assets/352ce515-99ad-48bb-8121-2f257e107685" />

#### After Login User will see : 
<img width="1280" height="832" alt="Screenshot 2026-01-13 at 18 40 15" src="https://github.com/user-attachments/assets/15f323c4-9a2e-4e93-b9b3-f4267ec61c69" />
<img width="1280" height="832" alt="Screenshot 2026-01-13 at 18 41 04" src="https://github.com/user-attachments/assets/9ff4bb70-655e-4fb9-8153-86eca9385bcd" />
<img width="1280" height="832" alt="Screenshot 2026-01-13 at 18 41 18" src="https://github.com/user-attachments/assets/c08d0aae-d0b4-475a-851c-1864363e47b9" />

---

## 🚀 Learning Outcomes

- Django project setup
- Models & database interaction with ORM
- URL routing
- Rendering templates
- Managing static files

---

## 🔮 Future Enhancements

- ✔ Likes & comments
- ✔ User profiles

---

## 👨‍💻 Author
```text
Nikhil Kalamkar
Backend Developer | Python Enthusiast
```
