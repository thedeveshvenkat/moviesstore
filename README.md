## GT Movies Store

A full-stack movie store web app built with Django for CS 2340 (Objects and Design) at Georgia Tech.

Live Demo at: https://deveshvenkat.pythonanywhere.com

## Features
- User signup, login, and logout
- Browse and search movies by title
- Session-based shopping cart that converts to saved orders at checkout
- Order history page for each user
- Create, edit, and delete movie reviews
- Report inappropriate reviews, which hides them from the page
- Django admin panel for managing users, movies, reviews, and orders
- Responsive layout

## Tech Stack
Python, Django 5.0, SQLite, HTML/CSS, Bootstrap, deployed on PythonAnywhere

## To Run Locally
    git clone https://github.com/thedeveshvenkat/moviesstore.git
    cd moviesstore
    python -m venv venv
    source venv/bin/activate
    pip install django==5.0 pillow
    python manage.py migrate
    python manage.py runserver

Then open http://127.0.0.1:8000.
