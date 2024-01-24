---
layout: use-cases
title: Use Cases
permalink: /use-cases/
toc: true
---

{% for use_case in site.use_cases %}
# {{ use_case.name }}

{{ use_case.content | markdownify | inject_anchors }}
{% endfor %}