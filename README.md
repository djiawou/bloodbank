# One tup command
# create the environment variables
    python3 -m venv venvname
    source venvname/bin/active
# download the dependences
    pip install -r requirement.txt

# create superuser
    python3 manage.py createsuperuser
# run migration
    python3 manage.py makemigrations
    python3 manage.py migration

# run projet
python3 manage.py runserver            
