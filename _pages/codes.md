---
layout: archive
title: "Replication codes"
permalink: /codes/
author_profile: true
---

Links to replication code repositories are being added over time.

{% include base_path %}

{% for post in site.codes reversed %}
  {% include archive-single.html %}
{% endfor %}
