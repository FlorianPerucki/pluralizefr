================
French Pluralize
================

convert a singular word into plural according french grammar rules.

Usable as Jinja2 filter.

Licence
-------

BSD license (see LICENCE file)


Features
--------

1. Python code example:

.. code-block:: python

    import pluralizefr
    pluralizefr.pluralize("fromage") # return fromages


2. Jinja2 exemple:

.. code-block:: jinja2

    {{ 'fromage' | pluralize }}

