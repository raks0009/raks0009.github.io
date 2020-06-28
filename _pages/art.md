---
layout: archive
title: "paint splashing called art"
permalink: /art/
author_profile: true
---

{% include base_path %}

I possess no 'artsy' skills, but believe that it shouldn't desist me from expressing myself through drawings and paintings. Most of my 'work' is acrylic-on-canvas.

{% for post in site.art %}
  {% include archive-single.html %}
{% endfor %}

