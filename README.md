# Online Food Ordering and Management System

A student-friendly Django starter project for browsing a food menu, adding items to a cart, placing orders, and managing menu items through Django Admin.

## Technology
- Python 3.10+
- Django
- SQLite (default database)
- HTML, CSS, Bootstrap CDN

## Setup
```bash
python -m venv venv
# Windows: venv\Scripts\activate
# macOS/Linux: source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
Open http://127.0.0.1:8000/ for the app and http://127.0.0.1:8000/admin/ for administration.

## Starter features
- Food menu with categories, descriptions, and prices
- Session-based shopping cart
- Place an order with customer/contact details
- Order confirmation page
- Admin management for food items, categories, and orders

This is an educational starter project. It does not process real payments. Add authentication, validation, tests, and a payment provider only if required by your project specification.
