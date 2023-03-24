# Module quiz: Introduction to Django

1. Which of the following are some of the differences between the commands django-admin and manage.py? Select all that apply.
   - django-admin is a command-line utility and manage.py is a Python script.
   - manage.py is more convenient to use than django-admin.
   - There is no difference between django-admin and manage.py.
   - django-admin is installed in the Python environment when you install Django with PIP utility. The manage.py file is created inside each Django project folder.

   ```
   Answer: django-admin is a command-line utility and manage.py is a Python script.
   manage.py is more convenient to use than django-admin.
   django-admin is installed in the Python environment when you install Django with PIP utility. The manage.py file is created inside each Django project folder.

   ```

2. The urls.py file is present in the project package and the app package.
   - True
   - False
   ```
   Answer: True
   Explanation: The urls.py in the project folder defines the URLConf. The app’s urls.py is included in the project’s urlpatterns list.
   ```

3. What happens when the view function created inside the views.py file is modified while the development server is still running?
   - The development server will terminate.
   - The server will need to be restarted manually to reflect new changes.
   - The webpage in the browser is automatically reloaded to reflect the new changes.
   - The development server will automatically reload and changes will reflect on webpage reload.
   ```

   Answer: The development server will automatically reload and changes will reflect on webpage reload.

   Explanation: You will be able to see the changes server reload in the command prompt once you save the views.py file. On manually reloading the webpage, the new changes will be reflected.
   ```

4. Where is the manage.py file located?
   - Inside the app package folder
   - Inside the project's outer container folder
   - Inside the scripts folder of the current Python environment.
   - Inside the project package folder
   ```
   Answer: Inside the project's outer container folder
   Explanation: In the outer project folder, you’ll find the manage.py script along with the app package and the project package.
   ```

5. By default, Django's built-in development server runs on the local machine with IP address 127.0.0.1 and port 8000.
   - True
   - False
  
   ```
   Answer: True
   Explanation: The runserver command option for django-admin and manage.py starts the development server and listens to the incoming requests on port 8000 of the localhost by default.
   ```

6. Does the View layer in Django correspond to the View layer in MVC architecture?
   - Yes
   - No
   ```
   Answer: No
   Explanation: Django’s view layer performs the role of Controller in MVC architecture.
   ```

7. Which of the following statements is true about the view function? Select all that apply.
   - Interacts with the model layer
   - Receives the request object from the server.
   - Loads the template
   - Returns a response to the client 
   ```
   Answer: All options are correct
   ```

8. Which of the following statements are true about a model in Django? Select all that apply.
   - A model is a Python class
   - The Model defines the processing logic of the Django application.
   - Model class attributes are used to create a database table.
   - A Django Template fetches the data from a Model and displays it on a web page.
   ```
   Answer: A model is a Python class.
   Model class attributes are used to create a database table.
   ```

9. Which Python module is used from the command-line to create a virtual environment?
   - pip3 
   - shell
   - startapp  
   - venv
   ```
   Answer: venv
   Explanation: The Python virtual environment is created with the command python –m venv envname.
   ```

10. Which of these pre-built apps are installed in a Django project by default? Select all that apply.
  
  - django.contrib.auth
  - django.contrib.messages 
  - django.contrib.admin
  - postgress app

    ```
    Answer: django.contrib.auth
            django.contrib.messages
            django.contrib.admin
    ```


























1.
Question 1
Which of the following are some of the differences between the commands django-admin and manage.py? Select all that apply.

1 / 1 point

django-admin is a command-line utility and manage.py is a Python script.

Correct
Correct! manage.py should be run as a Python module. The django-admin is an executable file that is run in the terminal.


manage.py is more convenient to use than django-admin.

Correct
Correct! manage.py runs inside the project folder. When using django-admin, you must set --settings variable to the required project's settings.py file.


There is no difference between django-admin and manage.py.


django-admin is installed in the Python environment when you install Django with PIP utility. The manage.py file is created inside each Django project folder.

Correct
Correct! You will find manage.py in the project folder and django-admin in Python’s scripts folder. 

2.
Question 2
The urls.py file is present in the project package and the app package.

1 / 1 point

True


False

Correct
Correct! The urls.py in the project folder defines the URLConf. The app’s urls.py is included in the project’s urlpatterns list.

3.
Question 3
What happens when the view function created inside the views.py file is modified while the development server is still running? 

1 / 1 point

The development server will terminate.


The server will need to be restarted manually to reflect new changes.


The webpage in the browser is automatically reloaded to reflect the new changes.


The development server will automatically reload and changes will reflect on webpage reload.

Correct
Correct! You will be able to see the changes server reload in the command prompt once you save the views.py file. On manually reloading the webpage, the new changes will be reflected.

4.
Question 4
Where is the manage.py file located?

1 / 1 point

Inside the app package folder


Inside the project's outer container folder


Inside the scripts folder of the current Python environment.


Inside the project package folder

Correct
Correct! In the outer project folder, you’ll find the manage.py script along with the app package and the project package.

5.
Question 5
By default, Django's built-in development server runs on the local machine with IP address 127.0.0.1 and port 8000.

1 / 1 point

True


False

Correct
Correct! The runserver command option for django-admin and manage.py starts the development server and listens to the incoming requests on port 8000 of the localhost by default.

6.
Question 6
Does the View layer in Django correspond to the View layer in MVC architecture?

1 / 1 point

Yes


No

Correct
Correct! Django’s view layer performs the role of Controller in MVC architecture.

7.
Question 7
Which of the following statements is true about the view function? Select all that apply.

1 / 1 point

Interacts with the model layer

Correct
Correct! The view performs the CRUD operations on the models.


Receives the request object from the server.

Correct
Correct! The view function receives the request object from the server context.


Loads the template

Correct
Correct! The view loads a template, fills the context data, and returns it to the client browser.


Returns a response to the client

Correct
Correct! The view does return a HttpResponse to the client.

8.
Question 8
Which of the following statements are true about a model in Django? Select all that apply.

1 / 1 point

A model is a Python class

Correct
Correct! A model class represents a database table structure.


The Model defines the processing logic of the Django application.


Model class attributes are used to create a database table.

Correct
Correct! Django performs migration to construct a database table from the model attributes.


A Django Template fetches the data from a Model and displays it on a web page.

9.
Question 9
Which Python module is used from the command-line to create a virtual environment?

1 / 1 point

pip3


shell


startapp


venv

Correct
Correct! The Python virtual environment is created with the command python –m venv envname.

10.
Question 10
Which of these pre-built apps are installed in a Django project by default? Select all that apply.

1 / 1 point

django.contrib.auth

Correct
Correct! This app is added in INSTALLED_APPS by default.


django.contrib.messages 

Correct
Correct! This app is added in INSTALLED_APPS by default.


django.contrib.admin

Correct
Correct! This app is added in INSTALLED_APPS by default.


postgress app