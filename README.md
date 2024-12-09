#Pradip Rajendra Warkhade

# Django To-Do App

## Description
This is a simple To-Do application built using Django. It allows users to add tasks and view a list of tasks. The project demonstrates basic CRUD functionality and integrates Django with HTML/CSS.

---

## Features
- Add new tasks.
- View a list of tasks.

---

## Requirements
- Python 3.x
- Django (version >= 4.x)
- Git (for version control)

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/pradip292/TODO_APP_USING_DJANGO.git
```

### 2. Navigate to the Project Directory
```bash
cd todo_project
```

---

### 3. Set Up a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # For MacOS/Linux
venv\Scripts\activate     # For Windows
```

---

### 4. Install Dependencies
Install Django and other required libraries:
```bash
pip install django
```

---

### 5. Run Database Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 6. Run the Development Server
```bash
python manage.py runserver
```

---

### 7. Open the Application
- Open your web browser and navigate to:  
  [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## Project Structure
```
todo_project/
├── tasks/
│   ├── migrations/
│   ├── templates/
│   │   └── tasks/
│   │       ├── add_task.html
│   │       └── task_list.html
│   ├── static/
│   │   └── styles.css
│   ├── models.py
│   ├── views.py
│   ├── urls.py
├── todo_project/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
├── manage.py
└── README.md
```



## Contributing
Feel free to fork this repository and make contributions. For major changes, please open an issue first to discuss what you would like to change.

---

## License
This project is open-source and free to use. License details can be added here if required.

---

Let me know if you need help with screenshots or any additional sections! 😊
