---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

{% for post in site.software reversed %}
  <h2>{{ post.title }}</h2>
  <div>
    {{ post.content }}
  </div>
  <hr>
{% endfor %} 