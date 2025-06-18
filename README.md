# InfraStructure
InfraStructure
# 📚 College Portal Management System

This is a **Flask-based web application** that allows **students** and **faculty** to:
- Register
- Login
- Edit their profiles (with photo upload)
- Access personalized dashboards
- Manage hostel, transportation, booking, and alert pages

Data is securely stored in a **MongoDB** database.

---

## 🚀 Features

- Student and Faculty registration & login
- Profile editing with photo upload support
- Separate dashboards for Students and Faculty
- Session-based authentication
- MongoDB backend storage
- Flash messages for success and errors
- Routes for hostel management, attendance, transportation, alerts, and more
- Modular and scalable code structure

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Database**: MongoDB (local instance)
- **Frontend**: HTML5, CSS3 (Jinja2 templates)
- **Others**: WerkZeug, Pymongo, UUID for secure photo uploads

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/college-portal.git
   cd college-portal
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start MongoDB**
   - Make sure you have **MongoDB installed** and **running locally** on `mongodb://localhost:27017/`.

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Visit**
   ```
   http://127.0.0.1:5000/
   ```

---

## 📂 Project Structure

```bash
college-portal/
│
├── static/
│   └── uploads/           # Uploaded profile photos
│
├── templates/
│   ├── *.html             # All HTML pages (student/faculty dashboards, edit pages, etc.)
│
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## 🔒 Environment Variables (Optional)

You can improve security by moving your `SECRET_KEY` and `MongoDB URI` to a `.env` file.  
(Currently hardcoded for simplicity.)

---

## ✨ Future Improvements

- Password hashing (bcrypt)
- Admin dashboard for full control
- Email verification
- Cloud image storage (e.g., AWS S3)
- Mobile-responsive UI
- Improved file type checking for uploads

---

## 🧑‍💻 Author

- Built by [R.GOPINATH REDDY](https://github.com/rgopi143)
- Contributions welcome!

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

