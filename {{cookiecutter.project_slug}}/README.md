# {{ cookiecutter.project_name }}

Author: {{ cookiecutter.author_name }}

Modality: {{ cookiecutter.modality }}

---

This project uses {{ cookiecutter.modality }} data organized in BIDS format.
{% if cookiecutter.use_datalad == "yes" %}
This project uses datalad for data management.
{% endif %}