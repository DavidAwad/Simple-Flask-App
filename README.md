# Simple Flask Guest Book

A guest book is a simple app that allows a user to leave their name and a message, and see the other names and messages of users who have _signed_ before them.

This app is ment to be an example in building a simple [Flask](http://flask.pocoo.org/) app with GETs, POSTs, and inserting and reading from an SQL database using [dataset](https://dataset.readthedocs.org/en/latest/).

## Get your PIP (your dependency manager)

### If you have a mac

_if you have easy_install already, just skip to step 3, you can test by typing ```which easy_install``` in your terminal_

1. Download the distribute setup script to get easy_install
```
http://python-distribute.org/distribute_setup.py
```

2. Run the script to install easy_install (do this in the terminal)
```
python distribute_setup.py
```

3. easy_install pip (do this in the terminal)
```
easy_install pip
```

### If you're on Windows

1. Install pip-Win
```
https://sites.google.com/site/pydatalog/python/pip-for-windows
```

### If you're on Ubuntu

1. Install with Apt (in terminal)
```
sudo apt-get install python-pip
```

## Install Dependencies

1. In your terminal, pip install flask and dataset
```
pip install flask
pip install dataset
```

## Run the server

1. In your terminal, navigat to the repo's directory and run app.py
```
cd [REPO LOCATION]
python run.py
```

2. Access app from localhost:5000
