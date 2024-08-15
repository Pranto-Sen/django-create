# django-create


- On Windows, create and activate the virtual environment:
      ```bash
       py -3 -m venv .venv
      .venv\Scripts\activate
       ```

- On Linux/Mac, create and activate the virtual environment:
      ```bash
      python3 -m venv .venv
      source .venv/bin/activate
      ```
- install django
      ```bash
    pip install django
      ```
- Create a New Django Project
      ```bash
    django-admin startproject myproject
       ```
- Navigate to the Project Directory
      ```bash
   cd myproject
      ```
- Create a Django App
      ```bash
    python manage.py startapp myapp
       ```
- Add the App to INSTALLED_APPS
     ```bash
     myproject/settings.py

    INSTALLED_APPS = [
        
        'myapp',  # Add this line
            ]
     ```
- Run Initial Migrations
      ```bash
     python manage.py migrate
      ```
- Create Migrations for Your App (if applicable)
      ```bash
    python manage.py makemigrations myapp
       ```
- Apply Migrations
      ```bash
    python manage.py migrate
      ```
- Run the Superuser Creation Command
      ```bash
    python manage.py createsuperuser
      ```
- Run the Development Server 
      ```bash
    python manage.py runserver
      ```
  
