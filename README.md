# API_FLASK
to run the apllication:
#bash
sqlite3 /tmp/my_data_base.db < schema.sql #this file is to define the table should be used 
#python
from contextlib import closing
from my_api import init_db
init_db()
#bash
python my_api.py

the folder templates and static is to define the aplicatin 
