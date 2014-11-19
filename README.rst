PaCT SMS API Reference Client
=============================

Requirements
------------

To run this script you need Python 2 and the third-party library
'restkit', available from the Python Package Index:

https://pypi.python.org/pypi/restkit


Simple usage
------------

This is set up to use virtualenv so you don't break your system Python environment.

Setup [from scratch]:

From this directory, do:

  $ virtualenv venv
  $ . venv/bin/activate
  $ pip install -r requirements.txt

Or as a one-liner you can copy and paste:

  virtualenv venv && . venv/bin/activate && pip install -r requirements.txt

Then do:

  $ python pact-api-client --help

