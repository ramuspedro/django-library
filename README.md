# Django Library


## Tradition Django Project

```
# install django
pipenv install django==2.0

# enter shell
pipenv shell

# start project
django-admin startproject library_project .

# migration
python manage.py migrate

# run server
python manage.py runserver

# book app
python manage.py startapp books

# migration
python manage.py migrate

# after insert data in model of books
python manage.py makemigrations books

# migration
python manage.py migrate

# create super user
python manage.py createsuperuser

# create books url
touch books/urls.py

# create folder template of book
mkdir books/templates

# books folder
mkdir books/templates/books

# book list html
touch books/templates/books/book_list.html
```

## Rest Django Project

```
# install django rest framework
pipenv install djangorestframework==3.8.2

# create api
python manage.py startapp api

# create urls for api
touch api/urls.py

# create serializer
touch api/serializers.py
```