# Restful Api with the Python Flask Framework

## Getting the Project

To install clone the github repository

```php
git clone https://github.com/bmehler/python-flask-crud.git
```

## Create a virtual environment
```bash
mkdir python-flask-restapi
$ cd python-flask-restapi
$ python3 -m venv venv
```

## Create a virtual environment
```bash
$ cd python-flask-crud
$ python3 -m venv venv
```
## Activate the environment
```bash
. venv/bin/activate
```

## Install the Flask Framework
```bash
pip install Flask
```

## Install MySQL
```bash
pip install flask-mysql
```

### Connect a Database Connenction
```python
app.config['MYSQL_DATABASE_HOST'] = db_host
app.config['MYSQL_DATABASE_PORT'] = db_port
app.config['MYSQL_DATABASE_USER'] = db_user
app.config['MYSQL_DATABASE_PASSWORD'] = db_password
app.config['MYSQL_DATABASE_DB'] = db_database
```

### Create a Database Table
The database table used in this example is
```bash
cars
```

### Run the Application with
```bash
flask --app init run
```