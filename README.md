# Student-data-management-system- Django & MySQL

## Project Overview
This project is a **Student Management System** developed using the **Django framework** with **MySQL** as the backend database.  
It demonstrates core web development and database concepts such as **CRUD operations**, relational databases, and Django’s MVC (MVT) architecture.

The application allows users to manage student records through:
- A **custom web interface** built using HTML
- The **Django Admin Panel** for backend management

---

## Tech Stack
- **Backend:** Django (Python)
- **Database:** MySQL
- **Frontend:** HTML
- **Tools:** MySQL Workbench, Django Admin, Command Prompt

---

## Features
- Create, view, update, and delete student records (CRUD)
- MySQL database integration with Django ORM
- Admin panel for managing students
- Clean project structure following Django standards

---

## Project Structure
- django_project/
- │
- ├── firstproj/
- │ ├── firstproj/
- │ ├── students_app/
- │ ├── manage.py
- │
- ├── README.md

## How to Run the Project (Locally)

- 1. Clone the repository:
   ```bash
   git clone <repository-url>
- 2. Navigate to the project directory:
  ```bash
  cd django_project
- 3. Activate virtual environment:
  ```bash
  myvenv\Scripts\activate
- 4. Navigate to Django project folder:
   ```bash
  cd firstproj
- 5. Run the development server:
  ```bash
  python manage.py runserver
- Open in browser:
- Student App: http://127.0.0.1:8000/
- Admin Panel: http://127.0.0.1:8000/admin/

Admin access is enabled using Django’s built-in superuser functionality.

### Outputs
<img width="1149" height="517" alt="Screenshot 2026-01-06 065811" src="https://github.com/user-attachments/assets/35fd5a30-278c-4f75-a45b-40016cd7603b" />

<img width="1341" height="676" alt="Screenshot 2026-01-06 073440" src="https://github.com/user-attachments/assets/5976d93f-7f7b-495f-bd2e-975a358a5e38" />

<img width="1342" height="655" alt="Screenshot 2026-01-06 225127" src="https://github.com/user-attachments/assets/2862c204-523c-41ce-88c2-262f40760de0" />

## Django Admin Panel

The project leverages Django’s built-in admin interface for secure backend management. Student records can be added, updated, and deleted through the admin panel with authentication and authorization enabled.

<img width="1355" height="669" alt="Screenshot 2026-01-06 073521" src="https://github.com/user-attachments/assets/d357bc03-51a2-4897-88b9-c30f8b92a78d" />

<img width="1360" height="670" alt="Screenshot 2026-01-06 073500" src="https://github.com/user-attachments/assets/654f4ec7-164f-4a44-b1f3-987e5ae7ee75" />
