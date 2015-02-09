# Flask-Blog
Blog in Flask
3.2. Installing third-party modules
PyPI, The Python Package Index maintains the list of Python packages available. The third-party module developers usually register at PyPI and uploads their packages there.

The standard way to installing a python module is using pip or easy_install. Pip is more modern and perferred.

Lets start with installing easy_install.

Download the easy_install install script ez_setup.py.
Run it using Python.
That will install easy_install, the script used to install third-party python packages.

Before installing new packages, lets understand how to manage virtual environments for installing python packages.

Earlier the only way of installing python packages was system wide. When used this way, packages installed for one project can conflict with other and create trouble. So people invented a way to create isolated Python environment to install packages. This tool is called virtualenv.

To install virtualenv:

$ easy_install virtualenv

Installing virtualenv also installs the pip command, a better replace for easy_install.

Once it is installed, create a new virtual env by running the virtualenv command.

$ virtualenv flask

On UNIX/Mac OS X:

$ source flask/bin/activate

$ pip install flask

$ pip install flask-login

$ pip install flask-openid

$ pip install flask-mail

$ pip install flask-sqlalchemy

$ pip install sqlalchemy-migrate

$ pip install flask-whooshalchemy

$ pip install flask-wtf

$ pip install flask-babel

$ pip install guess_language

$ pip install flipflop

$ pip install coverage

