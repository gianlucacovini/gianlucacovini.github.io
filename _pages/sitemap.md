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

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% assign visible_docs = collection.docs | where_exp: "post", "post.sitemap != false and post.hidden != true and post.published != false" %}
    {% if visible_docs.size > 0 %}
      {% capture label %}{{ collection.label }}{% endcapture %}
      {% if label != written_label %}
        <h2>{{ label }}</h2>
        {% capture written_label %}{{ label }}{% endcapture %}
      {% endif %}

      {% for post in visible_docs %}
        {% include archive-single.html %}
      {% endfor %}
    {% endif %}
  {% endunless %}
{% endfor %}
