# django-ecommerce-boilerplate

This is a modular Django eCommerce boilerplate project built to help get started quickly building Django ecommerce web projects quickly.

## Features

- Modular apps for Orders, Cart, Products, Users, Payments, Shipping, and Reviews.
- Class-based views and Django REST Framework for API support.
- Example configurations for development.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/V-FOR-VEND3TTA/django-ecommerce-boilerplate.git
   cd ecommerce_project
   ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run migrations:
    ```bash
    python manage.py migrate   
    ```
4. Start the development server:
    ```bash
    python manage.py runserver
    ```

Access the project at http://127.0.0.1:8000/.

## Suggestions for Extensions
- Add internationalization support with Django's `gettext` and `i18n`.
- Integrate caching using Redis.
- Customize the admin panel with `django-grappelli` or `django-jet` or a custom built admin with Bootstrap or React.