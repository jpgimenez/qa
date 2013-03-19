====================================
Quality Assurance for Plone projects
====================================

Life, the Universe, and Everything
----------------------------------

Buildout configuration and tools for providing Quality Assurance for Plone projects.

Don't Panic
-----------

This repository contains a Buildout configuration to include Quality Assurance
tools in Plone projects.

The following tools are provided:

`createzopecoverage`_
    Single script to create test coverage reports.

`flake8`_
    A wrapper around `Pyflakes, pep8 and Ned Batchelder's McCabe script.

coverage.sh
    Single script to check if a minimum test coverage is assured. We could
    skip this if createzopecoverage could provide at some point this
    information directly.

`z3c.dependencychecker`_
    Checks which imports are done and compares them to what's in setup.py and
    warn when discovering missing or unneeded dependencies.

Mostly Harmless
---------------

Got an idea? Found a bug? Let me know by `opening a support ticket`_.

.. _`createzopecoverage`: https://pypi.python.org/pypi/createzopecoverage
.. _`flake8`: https://pypi.python.org/pypi/flake8
.. _`pep8`: https://pypi.python.org/pypi/pep8
.. _`pyflakes`: https://pypi.python.org/pypi/pyflakes
.. _`z3c.dependencychecker`: https://pypi.python.org/pypi/z3c.dependencychecker
.. _`opening a support ticket`: https://github.com/hvelarde/qa/issues
