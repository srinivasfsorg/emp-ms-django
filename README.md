# Title
Django application to perform CRUD operations

# Technologies used
Frontend:  HTML

Backend: Django

Database: SQL


#Execution Flow
* Clone the project:
```
$ git clone https://github.com/srinivasfsorg/emp-ms-django.git
```

* Install required packages:
```
$ cd  repo directory && 
  $ pip3 install -r requirements.txt
```

* Make migrations to database:
```
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```
-----------------------------------------------------------------------------------------------------------------------
* Run server:
*  To run locally
```
$ python manage.py runserver 
```
-----------------------------
To Run in Cloud
```
$gunicorn main.wsgi --bind 0.0.0.0:8000
```
-----------------------------------------------------------------------------------------------------------------------
* Testing

http://127.0.0.1:8000 
------------------

http://<Public_ip>:8000



