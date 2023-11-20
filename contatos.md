---
layout: page
title: Contatos
description: Uma lista de todos os contatos relacionados ao curso.
nav_order: 6
---

<h1 align="center"><span style='font-weight: bold;'>Contatos</span></h1>

## Coordenadores

{% assign coordenadores = site.staffers | where: 'role', 'Coordenador' %}
{% for staffer in coordenadores %}
{{ staffer }}
{% endfor %}

{% assign professores = site.staffers | where: 'role', 'Professor' %}
{% assign num_professores = professores | size %}
{% if num_professores != 0 %}

## Professores

{% for staffer in professores %}
{{ staffer }}
{% endfor %}
{% endif %}
