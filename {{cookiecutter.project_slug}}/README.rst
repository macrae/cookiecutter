{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}

.. image:: https://circleci.com/gh/WindfallData/{{ cookiecutter.project_slug }}.svg?style=svg&circle-token=abcdefghijklmnopqrstuvwxyz
    :target: https://circleci.com/gh/WindfallData/{{ cookiecutter.project_slug }}

{{ cookiecutter.project_short_description }}

* Documentation: https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io.

Features
--------

* TODO

Credits
-------

This package was created with Cookiecutter_ and the `WindfallData/cookiecutter`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`WindfallData/cookiecutter`: https://github.com/WindfallData/cookiecutter
