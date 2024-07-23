---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">For the full up-to-date list of publications see <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>. Below I highlight some of my most important work. </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
