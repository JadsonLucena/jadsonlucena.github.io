---
layout: default
title: Professional Résumé
---

{% capture resume_source %}{% include_relative README.md %}{% endcapture %}
{{ resume_source | markdownify }}
