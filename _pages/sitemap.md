---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
  {% unless post.sitemap == false or post.hidden == true or post.published == false %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% unless post.sitemap == false or post.hidden == true or post.published == false %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% assign wrote_collection_label = false %}

    {% for post in collection.docs %}
      {% unless post.sitemap == false or post.hidden == true or post.published == false %}
        {% unless wrote_collection_label %}
          <h2>{{ collection.label }}</h2>
          {% assign wrote_collection_label = true %}
        {% endunless %}

        {% include archive-single.html %}
      {% endunless %}
    {% endfor %}
  {% endunless %}
{% endfor %}
