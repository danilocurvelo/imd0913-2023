---
layout: page
title: Notícias
description: O feed de notícias da disciplina.
---

# Notícias

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
