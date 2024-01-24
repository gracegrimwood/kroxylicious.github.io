---
layout: use-cases
title: Use Cases
permalink: /use-cases/
toc: true
---

{% for use_case in site.use_cases %}
# {{ use_case.name }}

<div class="no_toc_section">
    {{ use_case.content | markdownify }}
</div>
{% endfor %}