# flask-2025-01

2025-01 - spinning up a test flask app

# Notes

To get the initial python project created, I'm using this:
* https://medium.com/@Mr_Pepe/setting-your-python-project-up-for-success-in-2024-365e53f7f31e

With this in place, I can do things like...

```
pip install -e .[dev]
pip list

tox run -e lint  # to lint the project
tox run -f test  # run tests
tox run -e docs  # generate docs
tox run -e build # build the package

tox run          # do all the above
```