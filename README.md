## README.md


# Office Employment Management System (OEMS)

This is a Django-based web application designed for managing office employee data, roles, and operations efficiently. The OEMS system provides a robust platform for handling essential administrative tasks in a centralized and user-friendly way.

## Features
- Employee management (add, update, delete employee records)
- Role-based access and permissions
- Reports generation for performance and attendance
- Secure and scalable backend using Django

## Prerequisites
- Python 3.8+
- Django 4.0+
- pip (Python package manager)
- Git

## How to Set Up

1. Clone the repository:
   ```bash
   git clone https://github.com/vshnvii/OEMS.git
   ```

2. Navigate to the project directory:
   ```bash
   cd OEMS/oems
   ```

3. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Apply migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

7. Open your browser and visit `http://127.0.0.1:8000/` to access the application.

## Project Structure
- **oems/**: Main project directory
- **oemsApp/**: Contains the core application logic (models, views, templates)
- **manage.py**: Django’s command-line utility for administrative tasks

## License
This project is for learning purpose only.

## credits
This project was made using a tutorial by NitMan Talks as a reference- https://youtu.be/XMP57hQif4M?si=WLfWmGlI3S0Skqfb.
```

