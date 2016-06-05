=============================
{{ cookiecutter.project_name }}
=============================

.. image:: https://badge.fury.io/py/{{ cookiecutter.repo_name }}.png
    :target: https://badge.fury.io/py/{{ cookiecutter.repo_name }}

.. image:: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}.png?branch=master
    :target: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}

{{ cookiecutter.project_short_description}}

Documentation
-------------

The full documentation is at https://{{ cookiecutter.repo_name }}.readthedocs.org.

Quickstart
----------

Install {{ cookiecutter.project_name }}::

    pip install {{ cookiecutter.repo_name }}

Then use it in a project::

    import {{ cookiecutter.app_name }}


Credits
---------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/trojsten/cookiecutter-djangopackage
