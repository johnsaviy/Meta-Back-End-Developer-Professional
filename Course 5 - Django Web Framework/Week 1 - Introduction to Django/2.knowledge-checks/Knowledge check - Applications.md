# Knowledge check: Projects and Apps

1. Which of the following statements are true about a Django app? Select all that apply.

- There can be more than one app in a Django project.
- A Django app is reusable.
- The app package folder contains a settings.py file where app-specific configuration is defined.
- A Django app must have at least one model in it.
   ```
   Answer: django-admin
   When you install Django framework software, the django-admin utility is copied into the scripts folder of the Python installation. It performs various administrative tasks, including creating a project.
   ```

2. Can the startapp command be used with the django-admin utility?

- Yes
- No
   ```
   Answer: Yes
   Explanation: The startapp command option is available with Django-admin and the manage.py script.
   ```

3. Which of the following are features of a view? Select all that apply.
  
- The request object is the mandatory argument for the view function.
- A view is a user-defined function.
- A view is mapped to a URL pattern.
- The view returns only an HTML response.
   
   ```
   Answer: The request object is the mandatory argument for the view function.
   A view is mapped to a URL pattern.
   A view is a user-defined function.

   Explanation: The view function receives the request command from the server context and processes the request data, namely parameters and the body.

    You need to specify which URL pattern invokes a particular view. This mapping is defined in the urls.py file of the app.
   ```

4. Which of the following statements about the urls.py file in the app folder is false? Select all that apply.
  
- The urls.py file at the app-level is included in the urlpatterns list of the project.
- The urls.py in the apps folder is the same as urls.py in the project folder.
- The URL patterns in the app are defined with the path() function.
- The urls.py file is not present in the app folder by default.
   ```

   Answer: The urls.py file at the app-level is included in the urlpatterns list of the project.
   The urls.py in the apps folder is the same as urls.py in the project folder.
   
   ```

5. True or False. While working on multiple setting files in Django projects, django-admin is preferred over manage.py for running the Django commands in the command line. 
   - True
   - False
   ```
   Answer: True
   Explanation: django-admin command is preferred in such cases as it allows you to give specific settings with the help of environment variable DJANGO_SETTINGS_MODULE
   ```
