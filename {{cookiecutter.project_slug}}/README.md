{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
# {{ cookiecutter.project_name }}

{% if is_open_source %}
[![pypi](https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg)](https://pypi.python.org/pypi/{{ cookiecutter.project_slug }})
[![Travis](https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg)](https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }})
[![Docs](https://readthedocs.org/projects/{{ cookiecutter.project_slug | replace("_", "-") }}/badge/?version=latest)](https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io/en/latest/?badge=latest)
{%- endif %}


{{ cookiecutter.project_short_description }}

Features
--------

* TODO

Credits
-------

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter)
and the
[hmaarrfk/cookiecutter-pypackage](https://github.com/hmaarrfk/cookiecutter-pypackage)
project template.

