# eCommerce Website Django

A fully functioning eCommerce website and application using the Python Django framework, that will communicate with Stripe to accept payments and will also receive data back to the admin for sale reporting.

![](screenshots/home.png)

 
## Feature
- User Creation and Authentication
- Add Categories of Products
- Add Products
- Add to Cart
- Payment Authentication using Stripe
- Order History and Detials for User
- Search Products
- Customer Reviews on Products
- Contact Us for Users
 
## Requirements
- Python 3.x

You can download Python [here](https://www.python.org/downloads/).

- Django 3.x

You can download Django [here](https://www.djangoproject.com/download/).

- Stripe Account

You can register on their website [here](https://dashboard.stripe.com/register).

## Usage:

You should start cloning this repository:

    $ git clone https://github.com/shivangmedhekar/eCommerce-Website-Django.git
   
After downloading the repository, you have to install the following Django Apps

- Stripe

For online payment

    $ pip install stripe
    
- Cripsy Forms

Build programmatic reusable layouts out of components, having full control of the rendered HTML without writing HTML in templates.  

    $ pip install django-crispy-forms

- Widget Tweaks

Tweak the form field rendering in templates, not in python-level form definitions. Altering CSS classes and HTML attributes is supported.

    $ pip install django-widget-tweaks
   
    
After installing the apps, you have to go ecommerce_project folder

    $ cd ecommerce_project/ecommerce_project
    
In this folder you have to create a **api_key.py** file and create a variable **publishable_key** and **secret_key** assign your keys in string format of stripe.

 `api_key.py` file:
 
    # Your API Key should be inside the double quotes.
    publishable_key = ""
    secret_key = ""
    
After that you should make migrations and migrate.

    $ python manage.py makemigrations
    $ python manage.py migrate
    
then you must run **manage.py** script with **python** like this:

    $ python manage.py runserver
    
After the server is up and running go to the web url provided by Django to view the web app in any broswer.
    

## Web App by
|  **Shivang Medhekar** |
| :---: |
| [![Shivang Medhekar](https://avatars2.githubusercontent.com/u/69140290?s=200&u=5df35a82b6d2b6b7b876dfdc22d451c92d30a5c6&v=4)](https://github.com/shivangmedhekar) | 
| <a href="https://github.com/shivangmedhekar" target="_blank">`github.com/shivangmedhekar`</a>| 



## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
