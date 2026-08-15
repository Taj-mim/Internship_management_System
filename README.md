# InternHub — Internship Management System

InternHub is a **Django-based Internship Management System** designed to connect students and companies while providing administrators with centralized control over the internship process.

The system supports **role-based authentication** for Students, Companies, and Administrators, with separate dashboards and functionality for each user type.

---

## 🚀 Features

### 🔐 Authentication

* Student registration
* Company registration
* User login and logout
* Role-based authentication
* Student dashboard
* Company dashboard
* Admin dashboard
* Secure session-based authentication

### 🎓 Student

Students can:

* Create an account
* Access their personal dashboard
* Explore internship opportunities
* Manage internship applications
* Track their internship activities

### 💼 Company

Companies can:

* Create a company account
* Access a company dashboard
* Create internship opportunities
* Find potential student candidates
* Manage internship applications

### 🛡️ Administrator

Administrators can:

* Manage users
* Manage students and companies
* Manage internship opportunities
* Manage applications
* Monitor the overall internship system

---

## 🏠 Landing Page

The InternHub homepage provides:

* Professional navigation bar
* Hero section
* Student registration
* Company registration
* Login
* About section
* Platform features
* Call-to-action section
* Contact information
* Professional footer
* Responsive layout

---

## 🛠️ Technologies Used

* **Python**
* **Django**
* **HTML5**
* **CSS3**
* **SQLite / MySQL**
* **Git & GitHub**

---

## 📂 Project Structure

```text
InternHub/
│
├── accounts/
│   ├── migrations/
│   ├── templates/
│   │   └── accounts/
│   │       ├── base.html
│   │       ├── home.html
│   │       ├── login.html
│   │       └── ...
│   │
│   ├── static/
│   │   └── accounts/
│   │       └── css/
│   │
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── InternHub/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/InternHub.git
cd InternHub
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create a superuser

```bash
python manage.py createsuperuser
```

### 7. Run the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

---

## 🔑 User Roles

| Role       | Purpose                                  |
| ---------- | ---------------------------------------- |
| 🎓 Student | Find internships and manage applications |
| 💼 Company | Post internships and manage applicants   |
| 🛡️ Admin  | Manage and monitor the entire platform   |

---

## 🔄 Authentication Flow

```text
                    InternHub
                       │
                       ▼
                  Authentication
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
       Student       Company       Admin
          │            │            │
          ▼            ▼            ▼
      Student       Company       Admin
      Dashboard     Dashboard     Dashboard
```

---

## 🌐 Main Pages

```text
/                       → Home
/login/                 → Login
/register/              → Registration
/register/student/      → Student Registration
/register/company/      → Company Registration
/dashboard/             → Main Dashboard
/student/dashboard/     → Student Dashboard
/company/dashboard/     → Company Dashboard
/admin/dashboard/       → Admin Dashboard
/logout/                → Logout
```

---

## 🔒 Security

InternHub uses Django's built-in authentication system and role-based access control to provide different functionality according to the authenticated user's role.

Protected dashboard pages are accessible according to the user's assigned role.

---

## 📌 Project Status

**Currently in development 🚧**

The authentication system and initial landing page have been implemented. Internship management, application workflows, and additional dashboard functionality will be developed as the project progresses.

---

## 🎯 Future Improvements

* Internship posting and searching
* Internship application workflow
* Student profile management
* Company profile management
* Application status tracking
* Admin management dashboard
* Email notifications
* Search and filtering
* Internship recommendations
* REST API integration
* Deployment to a production server

---

## 👩‍💻 Developer

**Fatema Taj Mim**

Computer Science & Engineering Student

Interested in Backend Development, Full-Stack Development, and AI.

---

## 📄 License

This project is developed for educational and portfolio purposes.
