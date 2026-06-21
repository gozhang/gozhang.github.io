---
layout: archive
title: "Research outputs"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Publications and preprints

{% assign main_publications = site.publications | where_exp: "post", "post.category != 'written-contribution'" | sort: "date" | reverse %}
{% for post in main_publications %}
  {% include archive-single.html %}
{% endfor %}

## Written contributions and discussions

{% assign written_contributions = site.publications | where: "category", "written-contribution" | sort: "date" | reverse %}
{% for post in written_contributions %}
  {% include archive-single.html %}
{% endfor %}
