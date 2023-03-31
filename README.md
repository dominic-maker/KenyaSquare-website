# KenyaSquare-website
Django Ecommerce Website
This is an ecommerce website implemented using Django. The website allows users to browse products, add them to their cart, and place orders. It also has an admin interface for managing products, orders, and users.

Getting Started
Prerequisites
To run this project, you will need:

Python 3.x
Django 3.x
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/django-ecommerce.git
Create a virtual environment and activate it:
bash
Copy code
python -m venv env
source env/bin/activate  # on Linux/MacOS
env\Scripts\activate  # on Windows
Install the required packages:
Copy code
pip install -r requirements.txt
Apply the database migrations:
Copy code
python manage.py migrate
Load some initial data:
bash
Copy code
python manage.py loaddata fixtures/products.json
Run the development server:
Copy code
python manage.py runserver
The website should now be accessible at http://localhost:8000/.

Usage
User Interface
The website has the following pages:

Home page: displays a list of featured products
Product list page: displays all products or products filtered by category
Product detail page: displays the details of a single product and allows the user to add it to their cart
Cart page: displays the items in the user's cart and allows them to update or remove items
Checkout page: allows the user to enter their shipping and payment information and place an order
Order confirmation page: displays the details of the user's order
Admin Interface
To access the admin interface, go to http://localhost:8000/admin/. You can log in using the credentials in the superuser.json fixture.

The admin interface allows you to manage products, orders, and users.

Contributing
If you find any bugs or want to suggest new features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
