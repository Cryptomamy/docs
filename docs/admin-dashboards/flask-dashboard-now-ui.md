title: Flask Dashboard Now UI

# [Flask Dashboard Now UI](https://appseed.us/admin-dashboards/flask-dashboard-nowui-design)

Open-Source Admin Dashboard with Argon Dashboard Design coded in **[Flask](https://palletsprojects.com/p/flask/)** - features:

<br />

- [SQLite database](https://www.sqlite.org/index.html)
- [SQLAlchemy ORM](https://www.sqlalchemy.org/)
- Session based authentication flow (login, register)
- Static Build via Frozen-Flask

<br />

![Flask Dashboard Now UI - Open-Source Admin Panel](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-nowui-design-intro.gif)

<br />

## Setup the environment
---

In order to use the boilerplate, we need [Python](/what-is/python/) and [Flask](/what-is/flask/) installed on the workstation. 
The Python can be downloaded from the [official website](https://www.python.org/) and Flask can be easily added using `PIP` command:

```bash
$
$ # Test the Python install 
$ python --version
$ Python 3.7.2
$
$ # install Flask using PIP
$ pip install Flask
$
```

<br />

## Build from sources
---

```bash
$ # clone the sources
$ git clone https://github.com/app-generator/flask-now-ui-dashboard.git
$ cd flask-now-ui-dashboard
$
$ # install modules using a virtualenv
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # install deps 
$ pip install -r requirements.txt
$
$ # Create SQLite database using the Flask console
$ flask shell
>> from app import db
>> db.create_all()
>> quit() 
$
$ # SQLite database.db should be created in the app folder:
$ # app\database.db
$
$ # Set the FLASK_APP environment variable
$ (Windows) set FLASK_APP=app.py
$ (Unix) export FLASK_APP=app.py
$ (Powershell) $env:FLASK_APP = ".\app.py"
$ 
$ flask app.py
$ # app is running on port 5000
```

<br />

## Resources

- [Flask Dashboard Now UI](https://appseed.us/admin-dashboards/flask-dashboard-nowui-design) - product page
- [Flask Dashboard Now UI](https://flask-now-ui-dashboard.appseed.us/) - live DEMO
- [Flask Dashboard Now UI](https://github.com/app-generator/flask-now-ui-dashboard) - the source code published on Github