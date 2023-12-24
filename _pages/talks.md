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

* 1/24/2024, Biostatistics and Computational Biology Branch Seminar Series,
National Institute of Environmental Health Sciences (NIEHS)

* 5/1-3/2024, [STATGEN 2024](https://www.sph.pitt.edu/biostatistics/about/statgen-2024)

* 6/14/2024, Pitt Senior Vice Chancellor’s Research Seminar series


