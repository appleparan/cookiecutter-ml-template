=========================
Cookiecutter ML Template
=========================

.. image:: https://snyk.io/test/github/appleparan/cookiecutter-ml-template/badge.svg
    :target: https://snyk.io/test/github/appleparan/cookiecutter-ml-template/
    :alt: Known Vulnerabilities

.. image:: https://github.com/appleparan/cookiecutter-ml-template.py/actions/workflows/pytest.yml/badge.svg
    :target: https://github.com/appleparan/cookiecutter-ml-template.py/actions/workflows/pytest.yml
    :alt: Build Status

.. image:: https://readthedocs.org/projects/cookiecutter-ml-template/badge/?version=latest
    :target: https://cookiecutter-ml-template.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

Cookiecutter_ template for a Machine Learning pacakge.

* GitHub repo: https://github.com/appleparan/cookiecutter-ml-template/
* Documentation: https://cookiecutter-ml-template.readthedocs.io/
* Free software: MIT license

Features
--------

* Testing setup with ``unittest`` and ``python -m unittest`` or ``pytest``
* `GitHub Actions`_: Pre-configured GitHub Actions for automated testing with `pytest`_.
* Sphinx_ docs: Documentation ready for generation with, for example, `Read the Docs`_
* bump-my-version_: Pre-configured version bumping with a single command
* Auto-release to PyPI_ when you push a new tag to master (optional)
* Command line interface using Click (optional)

.. _Cookiecutter: https://github.com/cookiecutter/cookiecutter

Build Status
-------------

Linux:

.. image:: https://github.com/appleparan/cookiecutter-ml-template.py/actions/workflows/pytest.yml/badge.svg
    :target: https://github.com/appleparan/cookiecutter-ml-template.py/actions/workflows/pytest.yml
    :alt: Build Status

Quickstart
------------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/appleparan/cookiecutter-ml-template.py.git

Then:

* Create a repo and put it there.
* Install the dev requirements into a virtualenv. (``pip install -e ".[dev]"``)
* Register_ your project with PyPI.
  and activate automated deployment on PyPI when you push a new tag to main branch.
* Add the repo to your `Read the Docs`_ account + turn on the Read the Docs service hook.
* Release your package by pushing a new tag to main.
* Add a ``requirements.txt`` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.
* Activate your project on `snyk`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files
.. _Register: https://packaging.python.org/tutorials/packaging-projects/#uploading-the-distribution-archives

For more details, see the `cookiecutter-ml-template tutorial`_.

.. _`cookiecutter-ml-template tutorial`: https://cookiecutter-ml-template.readthedocs.io/en/latest/tutorial.html

Not Exactly What You Want?
--------------------------

Don't worry, you have options:

Similar Cookiecutter Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `https://github.com/audreyfeldroy/cookiecutter-pypackage`_: The original template this was forked from.

* `Nekroze/cookiecutter-pypackage`_: A fork of this with a PyTest test runner,
  strict flake8 checking with Travis/Tox, and some docs and ``setup.py`` differences.

* `tony/cookiecutter-pypackage-pythonic`_: Fork with py2.7+3.3 optimizations.
  Flask/Werkzeug-style test runner, ``_compat`` module and module/doc conventions.
  See ``README.rst`` or the `github comparison view`_ for exhaustive list of
  additions and modifications.

* `ardydedase/cookiecutter-pypackage`_: A fork with separate requirements files rather than a requirements list in the ``setup.py`` file.

* `lgiordani/cookiecutter-pypackage`_: A fork of Cookiecutter that uses Punch_ instead of bump2version_ and with separate requirements files.

* `briggySmalls/cookiecutter-pypackage`_: A fork using Poetry_ for neat package management and deployment, with linting, formatting, no makefiles and more.

* `veit/cookiecutter-namespace-template`_: A cookiecutter template for python modules with a namespace

* `zillionare/cookiecutter-pypackage`_: A template containing Poetry_, Mkdocs_, Github CI and many more. It's a template and a package also (can be installed with `pip`)

* `waynerv/cookiecutter-pypackage`_: A fork using Poetry_, Mkdocs_, Pre-commit_, Black_ and Mypy_. Run test, staging and release workflows with GitHub Actions, automatically generate release notes from CHANGELOG.

* Also see the `network`_ and `family tree`_ for this repo. (If you find
  anything that should be listed here, please add it and send a pull request!)

Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description.

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

Or Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.


.. _Sphinx: http://sphinx-doc.org/
.. _Read the Docs: https://readthedocs.io/
.. _synk: https://snyk.io/
.. _pytest: https://docs.pytest.org/en/latest/
.. _GitHub Actions: https://docs.github.com/en/actions
.. _bump-my-version: https://github.com/callowayproject/bump-my-version
.. _Punch: https://github.com/lgiordani/punch
.. _Poetry: https://python-poetry.org/
.. _PyPi: https://pypi.python.org/pypi
.. _Mkdocs: https://pypi.org/project/mkdocs/
.. _Pre-commit: https://pre-commit.com/
.. _Black: https://black.readthedocs.io/en/stable/
.. _Mypy: https://mypy.readthedocs.io/en/stable/

.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _`lgiordani/cookiecutter-pypackage`: https://github.com/lgiordani/cookiecutter-pypackage
.. _`briggySmalls/cookiecutter-pypackage`: https://github.com/briggySmalls/cookiecutter-pypackage
.. _`veit/cookiecutter-namespace-template`: https://github.com/veit/cookiecutter-namespace-template
.. _`zillionare/cookiecutter-pypackage`: https://zillionare.github.io/cookiecutter-pypackage/
.. _`waynerv/cookiecutter-pypackage`: https://waynerv.github.io/cookiecutter-pypackage/
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members