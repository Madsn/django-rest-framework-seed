django-rest-framework-seed
================

Start your Django (1.7+) API in seconds with this Django Rest Framework seed.

REQUIREMENTS: git, python, pip, linux command line

If you are looking to save a little time on starting your app, here is a working start with one example model, fully functioning User model, and token authentication.

Setup:

1. Clone down the repository, and enter directory

2. Run: python manage.py syncdb

3. Run: python manage.py runserver

4. Visit localhost:8000/admin <br>
        - Provide superuser username/password


There you have it! You have a simple, working API!

Feel free to comment on anything you see.


NOTES: <br>
        
        - You may have to include python version: python2.7 manage.py syncdb
        
        - Check out this tutorial if you have never started a django app before. 
          http://www.jeffknupp.com/blog/2012/10/24/starting-a-django-14-project-the-right-way/
          
        - I highly suggest using a virtualenv as to not mess with in-built dependencies
        
        - It would be a great idea to create a requirements.txt file to document your
          django and djangorestframework versions

        - if you are Mac OS X user and need to setup nodejs, read: http://shapeshed.com/setting-up-nodejs-and-npm-on-mac-osx/
        and remmber, that you will run node scripts/web-server.js 
