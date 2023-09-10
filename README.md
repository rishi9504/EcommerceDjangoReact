#  Ecommerce Website With Django + React









# Features
* Full featured shopping cart
* Product reviews and ratings
* Top products carousel
* Product pagination
* Product search feature
* User profile with orders
* Admin product management
* Admin user management
* Admin Order details page
* Mark orders as delivered option
* Checkout process (shipping, payment method, etc)
* PayPal / credit card integration


# Download & Setup Instructions

* 1 - Clone project: 
* 2 - cd EcommerceDjangoReact
* 3 - Create virtual environment: virtualenv myenv
* 4 - myenv\scripts\activate
* 5 - pip install -r requirements.txt
* 6 - python manage.py runserver

# Install react modules
* 1 - cd frontend
* 2 - npm install

# If you are having issues:
## With admin panel:
* Remove all the files except init.py in the migrations folder
* Run python manage.py makemigrations
* Run python manage.py migrate
* Run python manage.py createsuperuser and use the credentials used there for admin panel login
