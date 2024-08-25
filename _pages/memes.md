---
layout: archive
title: "Memes"
permalink: /memes/
author_profile: true
---

Some memes for you to enjoy!

<div class="memes-container">
  <div class="memes">
    {% for file in site.static_files %}
      {% if file.path contains '/memes/' and (file.extname == '.jpg' or file.extname == '.png') %}
        <img src="{{ file.path | relative_url }}" alt="Meme">
      {% endif %}
    {% endfor %}
  </div>
</div>