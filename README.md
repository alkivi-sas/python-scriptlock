python-scriptlock
==========================

[![Build Status](https://travis-ci.org/alkivi-sas/python-scriptlock.svg?branch=master)](https://travis-ci.org/alkivi-sas/python-scriptlock)
[![Requirements Status](https://requires.io/github/alkivi-sas/python-scriptlock/requirements.svg?branch=master)](https://requires.io/github/alkivi-sas/python-scriptlock/requirements/?branch=master)

Lock tool for scripts.

## Package

Example

```python
import time

from scriptlock import Lock

lock = Lock()
time.sleep(100)
```

Launch another one and see what happend

## Tests

Testing is set up using [pytest](http://pytest.org) and coverage is handled
with the pytest-cov plugin.

Run your tests with ```py.test``` in the root directory.

Coverage is ran by default and is set in the ```pytest.ini``` file.
To see an html output of coverage open ```htmlcov/index.html``` after running the tests.

TODO

## Travis CI

There is a ```.travis.yml``` file that is set up to run your tests for python 2.7
and python 3.2, should you choose to use it.

TODO
