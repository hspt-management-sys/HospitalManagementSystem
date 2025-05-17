# 🏥  Hospital Management System
This project is done using python full stack!

A full-featured **Hospital Management System** built using the **Django web framework**. This application allows admin, doctors, and patients to manage hospital workflows like appointments, patient records, and staff management—all through role-based access and a clean web interface.

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (with Django Templates)
- **Backend:** Python (Django Framework)
- **Database:** MySQL / SQLite
- **Tools:** VSCode, Git, Django Admin Panel

---

## 🚀 Key Features

### 👨‍⚕️ Admin
- Add/Edit/Delete doctors, patients, and staff
- View all appointments and manage schedules
- Access to the admin panel with CRUD functionality

### 🧑‍⚕️ Doctors
- View and manage appointments
- Update diagnosis and patient treatment records

### 👩‍💼 Patients
- Register/Login
- Book appointments with doctors
- View appointment history and prescriptions

---

## 📁 Project Structure

hospital_management/
├── hospital_app/        # Main Django app (models, views, urls)
├── hospital_management/ # Project settings and configuration
├── templates/           # HTML templates (Django templating engine)
├── static/              # CSS, JavaScript, images
├── db.sqlite3           # Default DB (or configure MySQL)
├── manage.py            # Django management script
└── requirements.txt     # Python dependencies


⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/yourusername/hospital-management-django.git
cd hospital-management-django
2. Create a Virtual Environment
python -m venv venv
mac:source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Configure Database (Optional)
By default, SQLite is used.

To use MySQL, update DATABASES in hospital_management/settings.py.

5. Run Migrations
python manage.py makemigrations
python manage.py migrate
6. Create Superuser (for admin access)
python manage.py createsuperuser
7. Start the Development Server
python manage.py runserver
Visit: http://127.0.0.1:8000

🙌 Acknowledgement


This project was inspired by an open-source Django Hospital Management System originally developed by Sumit Kumar under the MIT License. We initially referred to his YouTube tutorials and repository to understand the core structure of a Django-based full-stack application.

However, our version has significantly evolved through:

Resolving key execution errors and debugging backend issues.

Redesigning and customizing the frontend templates to improve usability.

Refactoring parts of the codebase to better suit our functional needs.

Gaining hands-on experience with Django views, models, authentication, and admin handling.

While the base helped us save time on boilerplate setup, the majority of the effort was spent on debugging, understanding how Django works under the hood, and building a working, customized solution for our version of a Hospital Management System.

We acknowledge the original source as a valuable learning reference and have adhered to the terms of the MIT License.
