Welcome to {{ cookiecutter.project_name }}'s documentation!
======================================

.. mdinclude:: ../README.md

Contents
========

.. toctree::
   :maxdepth: 1

   installation
   usage
   modules
   contributing

   {% if cookiecutter.create_author_file == 'y' -%}AUTHORS
   {% endif -%}HISTORY

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
