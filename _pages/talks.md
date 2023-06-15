---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

## Upcoming talks

* 8/10/2023, JSM 2023

* 11/9/2023, Biostatistics Seminar, University of North Carolina at Chapel Hill

* 12/16-18/2023, CMStatistics 2023


## Upcoming conferences

* 6/19/2023, WNAR
