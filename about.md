---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: Home
title: About
---

# About

See examples [examples of our work]({{ page.lesson-example}})
## Project
{{ site.description }}

## Funders
We gratefully acknowledge funding from the XYZ Founding Council, under grant number 'abc'.

## Team

The following people are members of our research team:
{% for team_meamber in site.team_members %}
- {{ team_member.name }}, role: {{ team_member.role }}
{% endfor %}



## Cite us
You can cite the project as:

> *The Carpentries 2019 Annual Report. Zenodo. https://doi.org/10.5281/zenodo.3840372*

## Contact us

