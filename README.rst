========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
        | |landscape|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/django-object-mapper/badge/?style=flat
    :target: https://readthedocs.org/projects/django-object-mapper
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/django-object-mapper.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/django-object-mapper

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/django-object-mapper?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/django-object-mapper

.. |requires| image:: https://requires.io/github/techdragon/django-object-mapper/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/django-object-mapper/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/techdragon/django-object-mapper/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/django-object-mapper

.. |landscape| image:: https://landscape.io/github/techdragon/django-object-mapper/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/django-object-mapper/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/django-object-mapper.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/django-object-mapper

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/django-object-mapper/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/django-object-mapper/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/django-object-mapper.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/django-object-mapper

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/django-object-mapper.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/django-object-mapper

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/django-object-mapper.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/django-object-mapper


.. end-badges

Django Object Mapper provides both relational and non-relational Object Mappers for connecting data sources into Django
based projects.

* Free software: BSD license

Installation
============

::

    pip install django-object-mapper

Documentation
=============

https://django-object-mapper.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
