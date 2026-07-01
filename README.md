# Simple Hospital Management System (Django)

A simple Hospital Management System built with Django, featuring an admin dashboard, a receptionist portal, and a doctor's portal to facilitate online patient consultation booking.

---

## 🚀 Features

- Django Admin panel for system management
- Receptionist dashboard for managing appointments
- Doctor dashboard for viewing and managing consultations
- Online patient consultation booking
- SQLite database (development) / PostgreSQL (production-ready)

---

## 🛠️ Tech Stack

- **Backend:** Python 3.x, Django
- **Database:** SQLite3 (dev), PostgreSQL (prod)
- **Frontend:** HTML, CSS (Django Templates)
- **Static Files:** Django staticfiles

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.8+
- pip
- virtualenv (recommended)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/Exquisite2020/Exquisite2020.git
cd Exquisite2020

# 2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment variables
cp .env.example .env
# Edit .env with your SECRET_KEY and other settings

# 5. Apply migrations
python manage.py migrate

# 6. Create a superuser
python manage.py createsuperuser

# 7. Run the development server
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 🔑 Environment Variables

Create a `.env` file in the root directory based on `.env.example`:

```
SECRET_KEY=your-secret-key-here
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
DATABASE_URL=sqlite:///db.sqlite3
```

---

## 📁 Project Structure

```
Exquisite2020/
├── home_test/          # Main app (models, views, urls)
├── mysite/             # Django project settings
├── static/             # Static files (CSS, JS, images)
├── manage.py           # Django management script
├── requirements.txt    # Python dependencies
└── .env.example        # Environment variable template
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Exquisite Writer**  
🌍 Ibadan, Nigeria  
🔗 [GitHub](https://github.com/Exquisite2020)
