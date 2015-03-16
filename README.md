# django-pluggable

## `runtests.py`

Your pluggable Django app will probably need to run an instance of Django
to be tested. `runtests.py` does that for you.

Install from pypi:

```shell
$ pip install django-pluggable
```

Then run:

```shell
$ export PYTHONPATH=`pwd`; runtests.py --settings='path.to.test_settings'
```

All apps that are in `INSTALLED_APPS` in your test settings will be tested.
