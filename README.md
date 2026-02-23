# Django Todo App

A complete Todo web application built with Django, featuring a modern UI with Tailwind CSS.

## Features

- ✅ Create, Read, Update, and Delete tasks
- ✅ Mark tasks as completed/active
- ✅ Filter tasks by status (All, Active, Completed)
- ✅ Set due dates for tasks
- ✅ Add descriptions to tasks
- ✅ AJAX toggle completion without page reload
- ✅ Beautiful, responsive UI with Tailwind CSS
- ✅ Django messages framework for user feedback

## Tech Stack

- **Backend**: Python + Django
- **Frontend**: Django Templates + Tailwind CSS (via CDN)
- **Database**: SQLite (for local development)
- **JavaScript**: Minimal JS for enhanced UX (toggle completion)

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd /path/to/todo_project
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Open your browser and navigate to:**
   ```
   http://127.0.0.1:8000/
   ```

8. **Allowed host in settings.py:**
      ```
      ALLOWED_HOSTS = [
       'localhost',
       '127.0.0.1',
       'todoapp-production-748d.up.railway.app'
       
   ]

9. **push updated local to github:**
   ```
      git add .
      git commit -m "sample message"
      git push
   ```

   
10. **Create account railway :**
   ```
   create account using github
   connect github projects
   select todo_app/
   ```


   
11 **Live Deployed URL (Railway):**
   ```
   https://todoapp-production-748d.up.railway.app/
   ```

![part_6 1](https://github.com/user-attachments/assets/501095e2-515c-4693-99ab-6fd31e8e85bf)



![part_6 2](https://github.com/user-attachments/assets/ca982438-64c1-4f49-9e35-3df27a0b7fdb)




