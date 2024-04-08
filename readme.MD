# Django ecommerce website
This is an ecommerce website built with django: it has the following functionality
* User registration
* Add billing address
* Checkout process
* Pay for order using stripe


## Installation
1. Download repository 
2. Create and activate virtual environment
    python -m venv venv
3. Install requirements
    pip freeze > requirements.txt
4. Migrate and start server
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
5. create an admin account
    python manage.py createsuperuser

## Example of app
Home page(all products are shown)


Login page(user logs in to website)

Signup page(user signs up to use service)

Profile page(shows user name and email)

Edit Profile page(allows user to edit name or email address)




Product detail page(information on selected product)

Shipping address form page(use enters shipping address of item)


Cart page(items in cart are shown)

Checkout page(fill in information to pay for item)



    




# modernhome
