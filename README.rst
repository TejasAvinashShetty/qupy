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
        | |codacy| |codeclimate|
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/qupy/badge/?style=flat
    :target: https://readthedocs.org/projects/qupy
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/TejasAvinashShetty/qupy.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/TejasAvinashShetty/qupy

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/TejasAvinashShetty/qupy?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/TejasAvinashShetty/qupy

.. |requires| image:: https://requires.io/github/TejasAvinashShetty/qupy/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/TejasAvinashShetty/qupy/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/TejasAvinashShetty/qupy/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/TejasAvinashShetty/qupy

.. |codecov| image:: https://codecov.io/gh/TejasAvinashShetty/qupy/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/TejasAvinashShetty/qupy

.. |codacy| image:: https://img.shields.io/codacy/grade/[Get ID from https://app.codacy.com/app/TejasAvinashShetty/qupy/settings].svg
    :target: https://www.codacy.com/app/TejasAvinashShetty/qupy
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/TejasAvinashShetty/qupy/badges/gpa.svg
   :target: https://codeclimate.com/github/TejasAvinashShetty/qupy
   :alt: CodeClimate Quality Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/TejasAvinashShetty/qupy/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/TejasAvinashShetty/qupy/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: GNU Lesser General Public License v3 (LGPLv3)

Installation
============

::

    pip install qupy

You can also install the in-development version with::

    pip install https://github.com/TejasAvinashShetty/qupy/archive/master.zip


Documentation
=============


https://qupy.readthedocs.io/


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
