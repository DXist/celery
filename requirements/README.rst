========================
 pip requirements files
========================


Index
=====

* `requirements/default.txt`

    The default requirements (Python 2.6+).

* `requirements/py25.txt`

    Extra requirements needed to run on Python 2.5.

* `requirements/py26.txt`

    Extra requirements needed to run on Python 2.6.

* `requirements/test.txt`

    Requirements needed to run the full unittest suite.



Examples
========

Running the tests using Python 2.5
----------------------------------

::

    $ pip -E $VIRTUAL_ENV install -U -r requirements/py25.txt
    $ pip -E $VIRTUAL_ENV install -U -r requirements/default.txt
    $ pip -E $VIRTUAL_ENV install -U -r requirements/test.txt

