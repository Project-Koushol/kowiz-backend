# Kowiz Backend

A Django-based backend application for the Kowiz project.

## Project Structure

```
kowiz-backend/
├── src/
│   ├── config/          # Django project configuration
│   │   ├── settings.py  # Main settings file
│   │   ├── urls.py      # URL routing
│   │   ├── wsgi.py      # WSGI configuration
│   │   └── asgi.py      # ASGI configuration
│   ├── kowiz_backend/   # Main application package
│   └── manage.py        # Django management script
├── tests/               # Test files
└── pyproject.toml       # Project dependencies
```

## Requirements

- Python >= 3.10
- Django >= 5.2.3

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd kowiz-backend
   ```

2. Install dependencies:
   ```bash
   poetry install
   ```

3. Run migrations:
   ```bash
   cd src
   python manage.py migrate
   ```

4. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

## Running the Server

```bash
cd src
python manage.py runserver
```

The server will start at `http://127.0.0.1:8000/`

## Admin Interface

Access the Django admin interface at `http://127.0.0.1:8000/admin/`

## Author

- **adib-the-noob** - mdadib550@gmail.com

## License

This project is currently without