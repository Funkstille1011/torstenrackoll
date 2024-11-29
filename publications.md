
---
layout: page
title: Publikationen
permalink: /publications/
---

# Publikationen

Hier finden Sie eine Liste meiner wissenschaftlichen Arbeiten:

{% for pub in site.data.publications %}
- **{{ pub.title }}** ({{ pub.year }}): {{ pub.journal }}
{% endfor %}
