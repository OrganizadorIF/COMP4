---
layout: page
title: Horários
description: The weekly event schedule.
nav_order: 5
---

<h1 align="center"> <span style='font-weight: bold;'> Horários </span> </h1>

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
