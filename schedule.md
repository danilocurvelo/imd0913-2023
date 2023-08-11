---
layout: page
title: Agenda
nav_order: 5
description: A agenda semanal do curso.
---

# Agenda Semanal

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
