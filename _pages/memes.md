---
layout: archive
title: "Memes"
permalink: /memes/
author_profile: true
---

Some memes for you to enjoy!

<div class="memes-container">
  <div class="memes">
    {% assign meme_files = site.static_files | where_exp: "file", "file.path contains '/memes/'" | sort: "name" %}
    {% for file in meme_files %}
      {% if file.extname == '.jpg' or file.extname == '.png' %}
        <img src="{{ file.path | relative_url }}" alt="Meme">
      {% endif %}
    {% endfor %}
  </div>
</div>