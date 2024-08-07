Blog Project
------------

This is a blog project built with Django and PostgreSQL. It allows users to create, edit, and delete blog posts, as well as comment on posts. The project demonstrates how to set up a basic blog application using Django, along with PostgreSQL as the database backend and HTML, CSS and Bootstrap.

Features 
---------

User authentication (registration, login, logout)
Create, edit, delete blog posts
Comment on posts
List all posts
View individual post details
Responsive design

Requirements 
-------------

Python 3.8+
Django 3.2+
PostgreSQL


Installation
-------------
1.Create a virtual environment:
	>> virtualenv venv
	>> venv\scripts\activate # for Mac user :source venv/bin/activate#
2.Install the required packages:
	>> pip install -r requirements.txt
3.Set up PostgreSQL:
Install PostgreSQL and create a database and user for the project.
Update the Database settings in qt_blog/settings.py with your PostgreSQL database details.
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_db_name',
        'USER': 'your_db_user',
        'PASSWORD': 'your_db_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}

4.Run database migrations:
	>> python manage.py migrate

5.Create a superuser:
	>> python manage.py createsuperuser

6.Start the development server:
	>> python manage.py runserver

7.Access the application:
Open your web browser and navigate to http://127.0.0.1:8000/.




Usage
------
Creating Blog Posts:
Navigate to the "New Post" page to create a new blog post.
Fill in the title and content of your post and submit the form.
Your post will be in Draft until you  publish  and visible to other users.

Editing and Deleting Blog Posts:
Navigate to the post you want to edit or delete.
If you are the author of the post, you will see options to edit or delete the post.
Make the necessary changes or confirm the deletion.

Commenting on Posts:
Navigate to the post you want to comment on.
Fill in the comment form and submit your comment.
Your comment will be added to the post.

Find Repository Here:  https://github.com/johnsonhabarugira/QT_Blog.git
