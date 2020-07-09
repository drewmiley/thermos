# movie-bag

To run:

1. `sudo mongod --dbpath /System/Volumes/Data/data/db`
1. `touch .env` and add `JWT_SECRET_KEY = 'SECRET_KEY'`
1. `pipenv shell`
1. `export ENV_FILE_LOCATION=./.env`
1. `python app.py`