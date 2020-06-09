# This app is for a TODO list. It was developed during Bottega classes.

We have created a pip environment. Use command pipshell to enter the environment.

to run the program use the command: python app.py in the command line, and open a browser window localhost:5000.

This uses flask, flask-squalchemy, and flask-marshmallow dependancies.

# Python Flask TODO Api
> Python Flask backend app for keeping track of todos.  It uses a flask sqlite database along with flask-marshmallow for object serialization/deserialization.  You can Post, Get, Patch, and Delete todos through flask routes.

>Create Database
-Make sure you are in your pipenv shell then go into a python repl and run the following commands

```
$ pipenv shell
$ python
>>> from app import db
>>> db.create_all()
```