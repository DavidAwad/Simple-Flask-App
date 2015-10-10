# Simple Flask Guest Book

A guest book is a simple app that allows a user to leave their name and a message, and see the other names and messages of users who have _signed_ before them.

This app is ment to be an example in building a simple [Flask](http://flask.pocoo.org/) app with GETs, POSTs, and inserting and reading from an SQL database using [dataset](https://dataset.readthedocs.org/en/latest/).

## Get your PIP (your dependency manager)

### If you have a mac

You should install [brew](http://brew.sh/) and instally python from there

```
brew install python 
```

### If you're on Windows

Install pip-Win
```
https://sites.google.com/site/pydatalog/python/pip-for-windows
```

### If you're on Ubuntu

Install with Apt (in terminal)
```
sudo apt-get install python-pip
```

## Install Dependencies

In your terminal, pip install flask and dataset
```
pip install flask
pip install dataset
```

## Run the server

In your terminal, navigat to the repo's directory and run app.py
```
cd [REPO LOCATION]
python run.py
```

Access app from localhost:5000
