======================
Cookiecutter PyPackage
======================

.. image:: https://circleci.com/gh/WindfallData/cookiecutter.svg?style=svg&circle-token=7d96c1b9bcd806bd85706e7bae3d222847ffac91
    :target: https://circleci.com/gh/WindfallData/cookiecutter

Cookiecutter_ template for a Python package.

* GitHub repo: https://github.com/macrae/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

* Testing setup with ``unittest`` and ``python setup.py test`` or ``pytest``
* Sphinx_ docs: Documentation ready for generation with, for example, `Read the Docs`_
* bump2version_: Pre-configured version bumping with a single command
* Auto-release to Artifactory when you push a new tag to master (TODO)

.. _Cookiecutter: https://github.com/audreyr/cookiecutter


Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/WindfallData/cookiecutter.git

Then:

* Create a repo and put it there.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Add the repo to your `Read the Docs`_ account + turn on the Read the Docs service hook.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

.. _Sphinx: http://sphinx-doc.org/
.. _bump2version: https://github.com/c4urself/bump2version
