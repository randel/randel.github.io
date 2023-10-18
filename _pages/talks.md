---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk! ## Upcoming conferences </a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

## Upcoming talks

* 11/9/2023, Biostatistics Seminar, University of North Carolina at Chapel Hill

* 12/17/2023, CMStatistics 2023

## Upcoming conferences

* 5/1-3/2024, [STATGEN 2024](https://www.sph.pitt.edu/biostatistics/about/statgen-2024)
