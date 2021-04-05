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
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/py-sar/badge/?style=flat
    :target: https://py-sar.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/IslamAlam/py-sar.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/IslamAlam/py-sar

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/IslamAlam/py-sar?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/IslamAlam/py-sar

.. |requires| image:: https://requires.io/github/IslamAlam/py-sar/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/IslamAlam/py-sar/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/IslamAlam/py-sar/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/IslamAlam/py-sar

.. |codecov| image:: https://codecov.io/gh/IslamAlam/py-sar/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/IslamAlam/py-sar

.. |version| image:: https://img.shields.io/pypi/v/py-sar.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/py-sar

.. |wheel| image:: https://img.shields.io/pypi/wheel/py-sar.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/py-sar

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/py-sar.svg
    :alt: Supported versions
    :target: https://pypi.org/project/py-sar

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/py-sar.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/py-sar

.. |commits-since| image:: https://img.shields.io/github/commits-since/IslamAlam/py-sar/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/IslamAlam/py-sar/compare/v0.0.0...master



.. end-badges

Python package for SAR.

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install py-sar

You can also install the in-development version with::

    pip install https://github.com/IslamAlam/py-sar/archive/master.zip


Documentation
=============


https://py-sar.readthedocs.io/


Development
===========

To run all the tests run::

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
