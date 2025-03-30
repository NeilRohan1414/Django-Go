# 1. to create virtual env --------- 
python -m venv "<name>"

# 2. to install Django --------------
python -m pip install Django

# 3. create the Django project inside the main folder-----
django-admin startproject "name of pro"

# 4. to run the server---------
python manage.py runserver

# 5. to specify the Django where to look for static files------in settings.py below the 
STATIC_URL type STATICFILES_DIRS=[os.path.join(BASE_DIR, 'your path to sources']

# 6. next to tell Django to create its own source file and put all the files ther-----------below 5th 
STATIC_ROOT = os.path.join(BASE_DIR, 'name of that file')

//////////////////

model and migrations

1. in settings in databases--------- .backend."your rdms <postgresql>" and unser name -------"your data name to connect with".
..........rest in binary book....
