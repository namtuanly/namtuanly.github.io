---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find my publications on <a href="{{site.author.googlescholar}}">my Google Scholar</a> or <a href="{{site.author.researchmap}}">my ResearchMap</a>.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
