# E-commerce Website

<p align="center">
    <img src="docs/images/1-the-product.png" width='500'/>
</p>

Build a full e-commerce website.

- With Payment Integration
- Ability to user shop as guest or registered user (Without creating an account /never have to register or create an account and shop as a authenticated user)

**Features:**

- Add items to cart.
- Edit cart (Add/ Remove items).
- On checkout, Add shipping details and then after payment is done you will be redirected to Home page.

Shipping address and payment method can be saved for guest users for long time.

**Techs Used:**

- Django
- JavaScript
- [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/).

Further it can be implemented with: React.js, REST API (Django Rest Framework) and Docker or Postgres for database.

Project Guide: [docs](docs/)

### Setup

1. Clone, Create Env, Install requirements and run server.

```bash
# Clone the repository
git clone

# Create virtual environment
python -m venv env

# Activate the environment
.\env\Scripts\activate

# Install requirements
pip install -r requirements.txt

# Run server
python manage.py runserver
```
