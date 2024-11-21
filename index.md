---
layout: default
title: Dit is een test site
---
# Voorbeeld voor een Github Pages site met Jekyll

## Voorbeeld van het gebruiken van data

Databestanden kun je plaatsen in _data en vervolgens kun je er doorheen loopen door site.data.<naam van het bestand> te gebruiken.

{% for person in site.data.peeps %}
- {{ person.name }} is {{ person.age }} jaar oud.
{% endfor %}

## Voorbeeld van het gebruiken van templating

In _layouts kun je layouts (templates) plaatsen die je kan aanroepen in de "front matter" van je pagina's. Front matter is de YAML die je bovenaan je pagina ziet, tussen de drie streepjes.

## Includes gebruiken

Je kunt includes gebruiken om stukken HTML te hergebruiken. Bijvoorbeeld een footer of een header. Deze kun je plaatsen in de _includes map.

## Externe templates

