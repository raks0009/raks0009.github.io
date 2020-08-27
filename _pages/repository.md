---
layout: archive
title: "Open Source Software"
permalink: /repository/
author_profile: true
---

{% include base_path %}

## GitHub Repositories

{% for post in site.repository-git reversed %}
  {% include archive-single.html %}
{% endfor %}

## Code Ocean Compute Capsules

{% for post in site.repository-codeocean reversed %}
  {% include archive-single.html %}
{% endfor %}

## Kaggle Datasets

{% for post in site.repository-kaggle reversed %}
  {% include archive-single.html %}
{% endfor %}
