# Products-API
Products API using Flask, SqlAlchemy and Marshmallow

## Quick Start Using Pipenv

``` bash
# Activate venv
$ pipenv shell

# Install dependencies
$ pipenv install

# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhst:5000)
python app.py
```
