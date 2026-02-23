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

8. **Live Deployed URL (Railway):**
   ```
   https://todoapp-production-748d.up.railway.app/
   ```


