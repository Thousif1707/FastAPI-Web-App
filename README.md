FastAPI Blog Application

A modern blog application built using FastAPI, featuring user authentication, post management, and async database operations.

---

📌 Features

- 🧑 User Registration & Authentication
- 📝 Create, Read, Update, Delete (CRUD) Blog Posts
- ⚡ Async database support
- 📂 Static & Media file handling
- 🧩 Modular project structure (routers, models, schemas)
- 🔄 Alembic migrations support

---

🛠️ Tech Stack

- Backend: FastAPI
- Database: PostgreSQL (or SQLite)
- ORM: SQLAlchemy (Async)
- Migrations: Alembic
- Templates: Jinja2
- Server: Uvicorn

---

📁 Project Structure

fastapi_blog/
│
├── alembic/            # Database migrations
├── routers/            # API routes
├── templates/          # HTML templates
├── static/             # Static files (CSS, JS)
├── media/              # Uploaded media
│
├── main.py             # Entry point
├── models.py           # Database models
├── schemas.py          # Pydantic schemas
├── database.py         # DB connection
├── config.py           # Configuration
├── auth.py             # Authentication logic
│
├── .env                # Environment variables
├── pyproject.toml      # Project dependencies
└── README.md

---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/YOUR_USERNAME/fastapi-blog.git
cd fastapi-blog

2️⃣ Create virtual environment

python -m venv .venv
source .venv/bin/activate   # Linux/Mac
.venv\Scripts\activate      # Windows

3️⃣ Install dependencies

pip install -r requirements.txt

---

🔑 Environment Variables

Create a ".env" file and add:

DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key

---

🗄️ Run Database Migrations

alembic upgrade head

---

▶️ Run the Application

uvicorn main:app --reload

Open in browser:
👉 http://127.0.0.1:8000

---

📘 API Documentation

- Swagger UI 👉 http://127.0.0.1:8000/docs
- ReDoc 👉 http://127.0.0.1:8000/redoc

---

📌 Future Improvements

- 🔐 JWT Authentication
- ❤️ Like & Comment system
- 📊 Admin dashboard
- 🌐 Deployment (Render / AWS)

---

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first.

---

📜 License

This project is licensed under the MIT License.

---

👨‍💻 Author

THOUSIF
GitHub: https://github.com/YOUR_USERNAME
