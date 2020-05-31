# flask-webapp
Web application using flask

# How to run application
- Install dependencies : `pip install flask flask-sqlalchemy flask-login authlib gc`
- Create Database : 
```
python

from app import db

db.create_all() 

exit()
```
- Run application : python app.py
