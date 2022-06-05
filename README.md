# vehicle-management-system
Django Restframework Project(CRUD)


# Installation:

pip install pipenv

### Create virtual env
pipenv shell


pip install django

pip install django restframework

pip install djongo

pip install pymongo==3.12.1


Install mongodb community server with compass.
https://www.mongodb.com/try/download/community


# Mongodb connection
DATABASES={"default": {"ENGINE": "djongo", "NAME": "vehicle_db"}}


# Create superadmin
python manage.py createsuperuser


# For creating admin
1. log in into django admin click on users.
2. Add user => enter username and password.
3. Give read, update permission


# For creating user
1. log in into django admin click on users.
2. Add user => enter username and password.
3. Give read permission
 
 
