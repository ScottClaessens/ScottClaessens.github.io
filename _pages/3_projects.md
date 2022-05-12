---
layout: page
title: projects
permalink: /projects/
description: click to see my different research interests
---

{% for project in site.projects %}

<a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
**{{ project.title }}**: {{ project.description }}
</a>

{% endfor %}