---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk! ## Upcoming conferences </a></p>

{% endif %}

{% for post in site.talks reversed 
% ## Upcoming conferences %}
  {% include archive-single-talk.html %}
{% endfor %}

## Upcoming talks

* 5/1-3/2024, [STATGEN 2024](https://www.sph.pitt.edu/biostatistics/about/statgen-2024)

* 6/14/2024, [Pitt Senior Vice Chancellor’s Research Seminar series](https://calendar.pitt.edu/event/integrating_single-cell_and_tissue_omics_population-level_cell_type-specific_insights)

* 8/3-8/2024, JSM


