# Create a main app file app.py inside the myapp folder and add necessary steps to run flask app

# Install flask restful follow the below commands

1. pip install flask_restful

# MySQL Connector

1. pip install mysql-connector-python

# MySQL Queries

1. create database country;
2. use country;
3. create table student( id int auto_increment, name varchar(100), email varchar(100), pass varchar(100), primary key(id));
2. Further query details => https://github.com/Guhanganesan/MySQL

# Flask CORS

1. pip install -U flask-cors

# Create a Service using this service.py module inside api folder

# Create a init module named __init__.py inside the api

# To install flask application follow the below commands

Flask Installation:-
Open your command prompt follow the steps to install virtualenv and flask to run Flask Wep Applications

1. Go to C:\Python37\Scripts\pip install virtualenv 
 (make sure that virtualenv is available or not, if it is not availble you have install the virtualenv)

2. Go to D:\myfolder (Create new empty folder as myfolder in D drive then move into the myfolder )

3. cd myfolder (move inside the folder)

4. D:\myfolder\ virtualenv venv    (install the supporting packages..)

5. D:\myfolder\ cd venv     (move inside the venv folder)

6. D:\myfolder\ venv\ mkdir myapp        (create new folder as myapp  )

7. D:\myfolder\ venv\ cd myapp        ( move inside the folder)

8. D:\myfolder\venv \myapp\ touch app.py (create python app file)

9. D:\myfolder\venv \myapp \cd.. (go back)

10.D:\myfolder\ venv\ cd Scripts (go into scripts)

11. D:\myfolder\ venv\ Scripts\ activate 

12. D:\myfolder\ venv\ Scripts\ cd.. (go back)

13. D:\myfolder\ venv\ pip install flask

14.D:\myfolder\ venv\  cd myapp   (move into the myapp folder) 

15. D:\myfolder\ venv\ myapp\ python app.py       (run the app)

16. Check in your browser: http://127.0.0.1:5000/

To Change IP Address: python -m flask run --host=172.16.3.64

# This app is running like

1. Get all => http://127.0.0.1:5000/api/v1.0/task
2. Get by id => http://127.0.0.1:5000/api/v1.0/task
3. Add (POST) by using  body = {
    "name":"anbu",
    "email":"anbu@gmail.com",
    "pass":1234
} 

with same url (1)










