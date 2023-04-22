---
title: Music
order: 1
---
## Improvisation

{% assign set = site.works | where: "category", "improv" | sort: "date" | reverse %}
{% include grid.html %}

## Compositions/Performance

{% assign set = site.works | where: "category", "piece" | sort: "date" | reverse %}
{% include grid.html %}

## Albums
{% assign set = site.works | where: "category", "solo" | sort: "date" | reverse %}
{% include grid.html %}
