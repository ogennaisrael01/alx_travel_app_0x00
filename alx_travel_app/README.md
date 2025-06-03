# ALX Travel App

A Django-based travel booking platform that allows users to list properties, make bookings, and leave reviews. The project uses Django REST Framework for API endpoints and includes Swagger documentation.

## Features

- User registration and management
- Property listing by hosts
- Booking system for guests
- Review and rating system
- API documentation with Swagger (drf_yasg)
- CORS support

## Project Structure

```
alx_travel_app_0x00/
│
├── manage.py                  # Django management script
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
│
├── alx_travel_app/            # Main Django project directory
│   ├── __init__.py
│   ├── settings.py            # Project settings
│   ├── urls.py                # Root URL configuration
│   ├── wsgi.py
│   └── asgi.py
│
└── listings/                  # App for property listings, bookings, reviews
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py              # Database models
    ├── serializers.py         # DRF serializers
    ├── views.py               # API views
    ├── urls.py                # App URL configuration
    ├── tests.py
    ├── migrations/
    │   └── __init__.py
    └── management/
        └── commands/
            └── seed.py        # Custom management command for seeding data
```