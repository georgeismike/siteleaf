---
title: benefits.md
date: 2017-10-08 00:28:00 Z
benefits:
- Free stuff
- more free stuff
---

{% for benefit in page.benefits %}
  {{ benefit }}
{% endfor %}