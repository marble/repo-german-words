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
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/repo-german-words/badge/?style=flat
    :target: https://readthedocs.org/projects/repo-german-words
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/marble/repo-german-words.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/marble/repo-german-words

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/marble/repo-german-words?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/marble/repo-german-words

.. |requires| image:: https://requires.io/github/marble/repo-german-words/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/marble/repo-german-words/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/marble/repo-german-words/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/marble/repo-german-words

.. |version| image:: https://img.shields.io/pypi/v/german-words.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/german-words

.. |wheel| image:: https://img.shields.io/pypi/wheel/german-words.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/german-words

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/german-words.svg
    :alt: Supported versions
    :target: https://pypi.org/project/german-words

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/german-words.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/german-words

.. |commits-since| image:: https://img.shields.io/github/commits-since/marble/repo-german-words/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/marble/repo-german-words/compare/v0.0.0...master



.. end-badges

How to compile a long list of german words.

* Free software: MIT license

Installation
============

::

    pip install german-words

You can also install the in-development version with::

    pip install https://github.com/marble/repo-german-words/archive/master.zip


Documentation
=============


https://repo-german-words.readthedocs.io/


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
