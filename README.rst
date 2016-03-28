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
        | |landscape| |scrutinizer|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-recipes/badge/?style=flat
    :target: https://readthedocs.org/projects/python-recipes
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/seanfisk/python-recipes.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/seanfisk/python-recipes

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/seanfisk/python-recipes?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/seanfisk/python-recipes

.. |requires| image:: https://requires.io/github/seanfisk/python-recipes/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/seanfisk/python-recipes/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/seanfisk/python-recipes/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/seanfisk/python-recipes

.. |landscape| image:: https://landscape.io/github/seanfisk/python-recipes/master/landscape.svg?style=flat
    :target: https://landscape.io/github/seanfisk/python-recipes/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/sf-recipes.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/sf-recipes

.. |downloads| image:: https://img.shields.io/pypi/dm/sf-recipes.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/sf-recipes

.. |wheel| image:: https://img.shields.io/pypi/wheel/sf-recipes.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/sf-recipes

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/sf-recipes.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/sf-recipes

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/sf-recipes.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/sf-recipes

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/seanfisk/python-recipes/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/seanfisk/python-recipes/


.. end-badges

Sean's common recipes for Python

* Free software: BSD license

Installation
============

::

    pip install sf-recipes

Documentation
=============

https://python-recipes.readthedocs.org/

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
