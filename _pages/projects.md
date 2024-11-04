---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% for post in site.projects %}
  <article>
    <h2>{{ post.title }}</h2>
    <p><a href="{{ post.paperurl | relative_url }}" target="_blank">Download Paper</a></p>
  </article>
{% endfor %}



