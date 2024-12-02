# About
This is just a basic django project to help me understand how these work:
- User Login and Registration
- Authentication and Authorization
- Models and Migrations
- Django Admin
- Forms
---
I didn't want to engage in a big project which could overwhelm me and yet i don't know the important aspects of django, so i chose this project inorder to learn more about Django

**CRM** stands for **Customer Relationship Management**. Think of it like a magic notebook where businesses keep track of their customers and all the important details about them.

# Installation
- clone the repository
  ```
  git clone https://github.com/khisareuben/Django-CRM.git
  ```
- cd into the directory where `manage.py` is (root directory of the project)
- create the virtual environment and activate it
  ```
  python -m venv env

  source env/Scripts/activate
  or
  source env/bin/activate #for linux/mac
  ```

- install the requirements
  ```
  pip install -r requirements.txt
  ```

- make changes to the `settings.py` and `mydb.py`
  ```
  change the user and password to your mysql credentials
  ```

- run the server
  ```
  python manage.py runserver
  ```
