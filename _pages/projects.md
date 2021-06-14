---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% for post in site.projects reversed %}
    {% include archive-single-talk.html %}
{% endfor %}