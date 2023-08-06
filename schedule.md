---
layout: page
title: Agenda
description: A agenda semanal do curso.
---

# Agenda Semanal

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
