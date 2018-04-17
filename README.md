This is the execution of the popular and official tutorial provided by the Django Documentation. By no means is it extensive, yet it provides a good first exposure to the Django framework for enthusiasts who want to begin somewhere.

Note: There are a couple of faults in the submitted code, including a bug which for some inexpliciable reason has not been rectified after adding the test condition and the corrected code. Also the website has two components, the admin and the polls. The polls are accessed by using polls/x where x is a number which indicates the number assigned to a question.

1. Setting up the app

Assuming Django is already set up on your system, use cd and enter a directory to store all your code into, and then run the following code:
       django-admin startproject mysite

This creates a mysite directory in the current directory. Startproject gives you something like this:

mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        wsgi.py



