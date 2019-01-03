.. image:: https://img.shields.io/pypi/v/fortifyapi.svg
   :target: https://pypi.org/project/fortifyapi
.. image:: https://img.shields.io/pypi/pyversions/fortifyapi.svg
.. image:: https://img.shields.io/travis/webbreaker/fortifyapi/master.svg
   :target: http://travis-ci.org/webbreaker/fortifyapi
   
Fortify API
***********

Fortify API is a Python RESTFul API client module for Fortify's `Software Security Center <https://saas.hpe.com/en-us/software/software-security-assurance-sdlc/>`_

Quick Start
~~~~~~~~~~~

Several quick start options are available:

- Build locally: ``pip install wheel setuptools && python setup.py build`` 
- Install with pip (recommended): ``pip install fortifyapi``
- `Download the latest release <https://github.com/webbreaker/fortifyapi/releases/latest/>`__.

Example
~~~~~~~

::

    # import the package
    from fortifyapi import fortify

    # setup fortify ssc connection information
    host = 'https://localhost:8443/'

    # instantiate the fortify api wrapper
    ssc = fortify.FortifyApi(host)

    # Do something

Supporting information for each method available can be found in the `documentation <https://webbreaker.github.io/fortifyapi/>`__.

Bugs and Feature Requests
~~~~~~~~~~~~~~~~~~~~~~~~~

Found something that doesn't seem right or have a feature request? Please open a new issue.

Copyright and License
~~~~~~~~~~~~~~~~~~~~~
.. image:: https://img.shields.io/github/license/webbreaker/fortifyapi.svg?style=flat-square

- Copyright 2018 Target Brands, Inc.
