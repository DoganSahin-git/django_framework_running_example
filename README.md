## Django Framework Running Example
Python Django app is built to show you a vey basic form of a blog application. It uses SQLite as a database.

create virtual environment
```
python3 -m venv venv
```
activate virtual environment
```
source venv/bin/activate
```
install dependencies
```
pip install -r requirements.txt
```
when you are under blogapp directory
```
python3 manage.py runserver
```
open a browser and give the adress 127.0.0.1:8000 to run the app
<br/>

###Hint:
Logon as admin from http://127.0.0.1:8000/admin with username:admin password:123+abc
You can also explore the db.sqlite3 file with your preffered db browser.
