# 📝 Blog App

A simple **Full Stack Blog Application** built with **Angular (Frontend)** and **.NET Core (Backend)**.

---

## 📂 Project Structure

```
zeeshan-45802/
│
├── frontend/   # Angular 17 Blog Frontend
│   └── blog-frontend
│
├── backend/    # .Node Blog Backend API
│   └── BlogApi
│
└── README.md
```

---

## 🚀 Features

* Create, edit, and delete blog posts
* Display list of posts dynamically
* Responsive UI (Angular Material / Bootstrap optional)
* RESTful API with JWT authentication
* SQL Server database support

---

## 🖥️ Frontend (Angular)

### Setup

```bash
cd frontend/blog-frontend
npm install
ng serve
```

Open in browser: **[http://localhost:4200/](http://localhost:4200/)**

---

## ⚙️ Backend (.NET Core API)

### Setup

```bash
cd backend/BlogApi
dotnet restore
dotnet run
```

API runs at: **[http://localhost:5000/](http://localhost:5000/)** (or configured port)

---

## 🔗 API Endpoints

| Method | Endpoint        | Description     |
| ------ | --------------- | --------------- |
| GET    | /api/posts      | Get all posts   |
| POST   | /api/posts      | Create new post |
| PUT    | /api/posts/{id} | Update a post   |
| DELETE | /api/posts/{id} | Delete a post   |

---

## 🛠️ Tech Stack

* **Frontend:** Angular 17, TypeScript, HTML, SCSS
* **Backend:** ASP.NET Core 7/8, C#, Entity Framework Core
* **Database:** SQL Server
* **Auth:** JWT Authentication
* **Version Control:** Git & GitHub

---

## 📌 How to Run Full Project

1. Start **backend API**:

   ```bash
   cd backend/BlogApi
   dotnet run
   ```

2. Start **frontend Angular app**:

   ```bash
   cd frontend/blog-frontend
   ng serve
   ```

3. Open browser → **[http://localhost:4200/](http://localhost:4200/)**

---

## 👨‍💻 Author

**Zeeshan Nawaz**
[GitHub Profile](https://github.com/Zeeshan732)

---
