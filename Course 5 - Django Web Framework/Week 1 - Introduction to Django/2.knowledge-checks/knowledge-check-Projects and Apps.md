# Knowledge check: Projects and Apps

1. What is the name of the command-line utility that Django uses internally to create a new Django project?Is a string in Python a sequence?

- manage.py
- pip
- startproject
- django-admin
   ```
   Answer: django-admin
   When you install Django framework software, the django-admin utility is copied into the scripts folder of the Python installation. It performs various administrative tasks, including creating a project.
   ```

2. In Python, what symbol is used for comments in code?

- manage.py
- models.py
- urls.py
- settings.py
   ```
   Answer: urls.py, settings.py
   Explanation: urls.py - This file defines the URL configuration of the project. It has a list of URL patterns mapped to the view functions defined in the Django app.

   settings.py - This file defines certain properties that are used by django-admin while performing various administrative tasks.

   ```

3. True or false. You don’t need to install the SQLite database for Django to use it as its backend. 

   - True
   - False
   
   ```
   Answer: True
   Explanation: When you create a Django project, it is configured to use SQLite database as its backend. Python has built-in support for SQLite.
   ```

4. Is it possible to use a MySQL database with a Django application? 
   - Yes
   - No
   ```
   Answer: Yes
   Explanation: You can use MySQL (or any other type of database). You need to change the DATABASE configuration in the settings.py file. Also, you should install the respective database driver.
   ```

5. Complete the following sentence. The ___________ command option of the manage.py script utility is used to launch the Django application.
   - shell
   - startapp
   - startproject
   - runserver
   ```
   Answer: runserver
   Explanation: This command starts Django’s built-in development server on the local machine at IP address 127.0.0.1 and port 8000.
   ```
