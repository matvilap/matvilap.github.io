---
title: Music
order: 1
---
## Albums
{% assign set = site.works | where: "category", "solo" | sort: "date" | reverse %}
{% include grid.html %}

## Improv

{% assign set = site.works | where: "category", "improv" | sort: "date" | reverse %}
{% include grid.html %}

## Compositions

{% assign set = site.works | where: "category", "piece" | sort: "date" | reverse %}
{% include grid.html %}
