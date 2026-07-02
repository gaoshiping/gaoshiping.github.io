---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of public pages and collection entries on this site. An XML version is available at [sitemap.xml]({{ base_path }}/sitemap.xml).

Pages
======

{% assign listed_pages = site.pages | where_exp: "item", "item.sitemap != false" %}
{% for post in listed_pages %}
  {% include archive-single.html %}
{% endfor %}

Publications
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Teaching
======

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
