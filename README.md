# 🚀 Full Stack App – FastAPI + React + PostgreSQL

A full-stack web application built using **FastAPI (backend)**, **React (frontend)**, and **PostgreSQL (database)**.

---

## 📁 Project Structure

```
FASTAPI/
├── frontend/              # React app
├── main.py                # FastAPI entry point
├── models.py              # Pydantic models
├── database.py            # DB connection setup
├── database_models.py     # SQLAlchemy models
├── requirements.txt       # Python dependencies
├── .gitignore
└── README.md
```

---

## ⚙️ Tech Stack

* **Backend:** FastAPI
* **Frontend:** React
* **Database:** PostgreSQL
* **ORM:** SQLAlchemy
* **Environment:** Python Virtual Environment

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/Raviteja2003/FASTAPI_CRUD.git
cd FASTAPI_CRUD
```

---

### 2️⃣ Create Virtual Environment

```
python -m venv venv
```

---

### 3️⃣ Activate Virtual Environment

#### Windows:

```
venv\Scripts\activate
```

#### Mac/Linux:

```
source venv/bin/activate
```

---

### 4️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

### 5️⃣ Setup Environment Variables

Create a `.env` file in the root directory:

```
DATABASE_URL=postgresql://username:password@localhost:5432/dbname
```

⚠️ If your password contains special characters like `@`, replace it with `%40`

---

### 6️⃣ Run FastAPI Server

```
uvicorn main:app --reload
```

---

### 7️⃣ Access API

* Swagger Docs: http://127.0.0.1:8000/docs
* Root Endpoint: http://127.0.0.1:8000/

---

## 📦 API Endpoints

| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | /products     | Get all products  |
| GET    | /product/{id} | Get product by ID |
| POST   | /product      | Add new product   |
| PUT    | /product/{id} | Update product    |
| DELETE | /product/{id} | Delete product    |

---

## 🚫 Ignored Files

The following are not pushed to GitHub:

```
myenv/
venv/
node_modules/
.env
__pycache__/
```

---

## 🧠 Notes

* Virtual environment is **not shared** — create your own.
* Database must be running locally (PostgreSQL).
* Make sure the DB exists before running the app.

---

## 🚀 Future Improvements

* Add authentication (JWT)
* Dockerize the application
* Deploy to cloud (AWS / Render / Railway)
* Connect frontend with backend APIs

---

## 👨‍💻 Author

Developed by **Ravi Teja**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
