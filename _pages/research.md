---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

### Ongoing and Completed Research Projects

{% for project in site.research reversed %}
- [{{ project.title }}]({{ project.url }})  
  {{ project.description }}
{% endfor %}
