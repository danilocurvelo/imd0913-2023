---
layout: page
title: Equipe
nav_order: 6
description: Uma lista de todos os membros da equipe docente.
---

# Equipe

## Professor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Professor Assistente

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
