
- On Windows, create and activate the virtual environment:
  ```
  py -3 -m venv .venv
  .venv\Scripts\activate
  ```

- On Linux/Mac, create and activate the virtual environment:
  ```
  python3 -m venv .venv
  source .venv/bin/activate
  ```
- install django
  ```
  pip install django
  ```
- Create a New Django Project
  ```
  django-admin startproject myproject
  ```
- Navigate to the Project Directory
  ```
  cd myproject
  ```
- Create a Django App
  ```
  python manage.py startapp myapp
  ```
- Add the App to INSTALLED_APPS
  ```
  myproject/settings.py

  INSTALLED_APPS = [
        'myapp',  # Add this line
            ]
  ```
- Run Initial Migrations
  ```
  python manage.py migrate
  ```
- Create Migrations for Your App (if applicable)
  ```
  python manage.py makemigrations myapp
  ```
- Apply Migrations
  ```
  python manage.py migrate
  ```
- Run the Superuser Creation Command
  ```
  python manage.py createsuperuser
  ```
- Run the Development Server 
  ```
  python manage.py runserver
  ```
  
