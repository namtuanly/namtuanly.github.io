---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find my publications on <u><a href="{{site.author.googlescholar}}">my Google Scholar</a></u> or <u><a href="{{site.author.researchmap}}">my ResearchMap</a></u>.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
