---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of the main pages on the site.

<h2>Pages</h2>

{% for nav_item in site.data.navigation.main %}
  {% assign nav_page = nil %}

  {% for page in site.pages %}
    {% if page.url == nav_item.url %}
      {% assign nav_page = page %}
    {% endif %}
  {% endfor %}

  {% if nav_page %}
    {% assign post = nav_page %}
    {% include archive-single.html %}
  {% else %}
    <p><a href="{{ base_path }}{{ nav_item.url }}">{{ nav_item.title }}</a></p>
  {% endif %}
{% endfor %}
