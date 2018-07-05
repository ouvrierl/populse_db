# populse_db [![Build Status](https://travis-ci.org/populse/populse_db.svg?branch=master)](https://travis-ci.org/populse/populse_db) [![codecov.io](https://codecov.io/github/populse/populse_db/coverage.svg?branch=master)](https://codecov.io/github/populse/populse_db)

SQLAlchemy based database API for Populse

# Tools

The API can support every database type, it takes an engine as entry

The database is managed thanks to the ORM SQLAlchemy

# Relational schema
![alt text](doc/schema.png "Relational schema")

Type {string, integer, float, date, datetime, time, json, list_string, list_integer, list_float, list_date, list_datetime, list_time, list_json}
	
# Installation

python directory must be added to $PYTHONPATH 

# Import

	import populse_db
	
# Tests

Unit tests written thanks to the python module unittest

Tested with Python2 and Python3

# Launch the tests

Add the directory python/populse_db in $PATH, or open this directory inside a terminal
	
	python2 Test.py  # With Python2
	
	python3 Test.py  # With Python3

