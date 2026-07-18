📝 My Todo App

A simple and clean Todo List web application built using Django, with user authentication so each user can manage their own personal tasks securely.

🚀 Features


User Signup / Login / Logout (Django authentication system)
Each user has their own private todo list
Add, update, and delete tasks
Clean and responsive UI using Bootstrap 5
Icons powered by Font Awesome
Personalized navbar showing logged-in username


🛠️ Tech Stack


Backend: Python, Django
Frontend: HTML, CSS, Bootstrap 5
Database: SQLite
Icons: Font Awesome


📂 Project Structure

todoproject/
├── accounts/        # Handles signup, login, logout
├── tasks/           # Handles todo CRUD operations
├── templates/       # HTML templates
├── manage.py
└── db.sqlite3

⚙️ Installation & Setup


Clone the repository


bash   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name


Create and activate a virtual environment


bash   python -m venv venv
   venv\Scripts\activate      # Windows
   source venv/bin/activate   # Mac/Linux


Install dependencies


bash   pip install -r requirements.txt


Run migrations


bash   python manage.py migrate


Start the development server


bash   python manage.py runserver


Open your browser and go to:


   http://127.0.0.1:8000/

👤 Author

Ayyaz
BCA Student | Python & Django Developer
Ahmedabad, Gujarat

📌 Note

This project was built as part of my BCA coursework and personal learning to strengthen my Django backend development skills.