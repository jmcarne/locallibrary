# Structure Python project
locallibrary  #website folder
    manage.py       # Script to run Django tools
    locallibrary/   # Website/project folder (created with django-admin)
    catalog/        # Application folder (created with manage.py)

# Creating project
django-admin startproject locallibrary

# Create catalog application or otis application (register app in settings.py file)
py -3 manage.py startapp catalog

# Check Python version
py -3 -V 

# Define tables in database for the models created previuosly
py -3 manage.py makemigrations
py -3 manage.py migrate