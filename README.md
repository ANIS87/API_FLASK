# API_FLASK
This API is to add and save text proposed by the user.
To run the API, please follow these steps:
#bash (linux)
home#sqlite3 /tmp/my_data_base.db < schema.sql #this file is to define the data base  should be used by the API 

#python

home#pyhton 
*>>>from contextlib import closing

*>>>from my_api import init_db

*>>>init_db()
#bash
home $ python my_api.py

the both folders templates and static are to define the API's design.
