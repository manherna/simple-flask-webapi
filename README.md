# Simple-flask-webapi

This is a simple WebApi project that uses [Flask web application framework](https://www.palletsprojects.com/p/flask/ "Flask's Homepage") and [SQLite](https://www.sqlite.org/index.html "SQLite's Homepage").

## 1.Environment configuration

Create a virtual environment for the project in the root folder (simple-flask-webapi).

```bash
python -m venv venv
# and start the environment
source venv/Scripts/activate
```

Then, install every python package required for the project:

```bash
pip install flask flask-sqlalchemy flask-login
```

Finally, set all flask variables for execution:

```bash
export FLASK_APP=app
export FLASK_DEBUG=1 # 0 for non-debug mode
flask run # runs the app and starts to listen to petitions
```
