# Meal Buddy – Django Food Ordering System

Meal Buddy is a full-stack Django web application that allows customers to browse restaurants, view menus, add items to cart, and complete payments using Razorpay.

---

## Features

### Customer
- User Signup & Signin
- Browse Restaurants
- View Menu
- Add to Cart
- Checkout with Razorpay
- Payment Success Page

### Admin
- Add Restaurant
- Update Restaurant
- Delete Restaurant
- Manage Menu Items

---

## Tech Stack

- Backend: Django (Python)
- Frontend: HTML, CSS
- Database: SQLite
- Payment Gateway: Razorpay
- Version Control: Git & GitHub

---

## Installation

```bash
git clone https://github.com/ganeswar-sahoo/meal-buddy.git
cd meal-buddy
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open in browser:
```
http://127.0.0.1:8000/
```

---

## Razorpay Setup

Add these in `settings.py`:

```python
RAZORPAY_KEY_ID = "your_key_id"
RAZORPAY_KEY_SECRET = "your_secret_key"
```

---

## Future Improvements

- Use Django built-in authentication
- Hash passwords
- Order history feature
- UI improvement
- Deploy to cloud

---

## Author

**Ganeswar Sahoo**  
Aspiring Full Stack Developer
