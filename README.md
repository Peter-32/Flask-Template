# Flask-Template

## Purpose

The basic files and directories of a Flask app.

## Installing

1. Clone this repo
2. Run:

			  rm -rf .git

3. Run `which python3`, see if you have python installed at /usr/local/bin/python3.6
4. Run the following inside the folder directory


        virtualenv -p /usr/local/bin/python3.6 venv

5. In the same folder run:


        pip install -r requirements.txt

6. Go to the app folder and run:


        FLASK_APP=hello.py flask run
