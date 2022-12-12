# Log Parser For Doxygen Warning Logs

# To run this script, you need to have Python 3 installed.
From the root folder of repository, run:
```$> python3 -m log_parser_richard -f <filename>```

# To run the unit tests for the parser
```$> pip install -e . -r requirements-dev.txt```
```$> python3 -m unittest discover tests/```

# To run pylint on the parser
```$> pip install -e . -r requirements-dev.txt```
```$> python3 -m pylint log_parser_richard```

# To run flake8 on the parser
```$> pip install -e . -r requirements-dev.txt```
```$> python3 -m flake8 src/```

# To run flake8 on the unit tests
```$> pip install -e . -r requirements-dev.txt```
```$> python3 -m flake8 tests/```
