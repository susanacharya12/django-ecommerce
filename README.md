# Django E-commerce Website

A fully functional e-commerce web application built with Django. This project supports multilingual content (English and Nepali), product filtering, image upload, simulated payment, and includes both admin and customer dashboards.

## Features

- Admin Panel
  - Add, update, delete products and categories
  - Manage customers and orders

- Customer Portal
  - User registration and login
  - View products by category
  - Add to cart, update cart, and checkout
  - View order history and status

- Multilingual Support
  - English and Nepali language support

- Product Image Upload
  - Upload and display product images

- Category Filtering
  - Filter products by category

- Payment Simulation
  - Simulated payment at checkout (demo only)

- Contact Us / Feedback Form

## Tech Stack

- Backend: Django 5.x
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite3 (default)
- Optional: MySQL or PostgreSQL with minor config changes
## Project Structure

```
django-ecommerce/
├── ecom/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
├── templates/
│   └── ecom/
│       ├── admin_base.html
│       ├── admin_dashboard.html
│       ├── customer_home.html
│       └── ...
├── static/
│   └── ...
├── locale/
│   └── ne/
├── media/
│   └── product_images/
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

## Setup Instructions

 1. Clone the Repository

```bash
git clone https://github.com/susanacharya12/django-ecommerce.git
cd django-ecommerce

2. Create a Virtual Environment and Activate It
python -m venv .venv
source .venv/bin/activate     # On Windows: .venv\Scripts\activate

3. Install Required Packages
pip install -r requirements.txt

4. Apply Migrations
python manage.py makemigrations
python manage.py migrate

5. Create Superuser
python manage.py createsuperuser

6. Run the Development Server
python manage.py runserver


