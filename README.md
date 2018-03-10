# Flask Landing page
A very lightweight landing page . It uses Python Flask and sqlite.

How it work's : http://alexbilokonenko.pythonanywhere.com/


# Setup
1. Install packages `sudo apt install python-pip python-virtualenv `
2. Create a python virtual environment: `virtualenv venv`
3. Enter virtual environment: `source venv/bin/activate`
3. Install python packages `pip install -r requirements.txt`
4. Initialize database: `export FLASK_APP=landing.py && flask initdb`
5. Run app in debug mode locally using : 'python landing.py'

Also See here: http://flask.pocoo.org/docs/0.11/installation/#installation
Leave virtual environment with `$ deactivate`

