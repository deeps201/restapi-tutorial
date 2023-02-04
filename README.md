# Restapi in Flask

To create a REST-API in Flask With JSON Web Token Authentication and Flask-SQLAlchemy ,for authentication and authorization and testing is done using Postman.


1) Create the folder

2) Create virtual environment

            virtualenv -p python3 .venv
            .venv/Scripts/activate

3) Install flask

             python -m pip install flask

4) Create requirements.txt file

            Flask-RESTful==0.3.8
            PyJWT==1.7.1
            Flask-SQLAlchemy==2.
  
    
* Use the following command to install requirements.txt file.

      pip install -r requirements.txt



* Creating Database.


* Go to Python Shell

            from api import app, db
            app.app_context().push()
            db.create_all()
            exit()

* Go to Sqlite3

            sqlite3 todo.db(filename)
            
            
[DEMO VIDEO]()
            

