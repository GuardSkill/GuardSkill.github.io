---
layout: archive
title: "Publications | 发表论文"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&user=96X3WCUAAAAJ&scilu=&scisig=AMD79ooAAAAAX0thrpp9uXfliGsMG0t2KcgY-ggz5HIB&gmla=AJsN-F4G4XpbAHDcV9l2GX4-07UEp04CBnzSJ3ozO2U-j08B7P7OkS-2aZW7HDara24t2swRx7q7yF-5lJPe5X-VTaEygOHF4MU6_UHLhd0NUTZZvcUubPQ&sciund=1769490103637609330}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
