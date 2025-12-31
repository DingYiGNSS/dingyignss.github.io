---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar or site.author.researchgate %}
  <div class="wordwrap">
    You can also find my publications on
    {% if site.author.googlescholar %}
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
    {% endif %}
    {% if site.author.googlescholar and site.author.researchgate %}
      and
    {% endif %}
    {% if site.author.researchgate %}
      <a href="{{ site.author.researchgate }}">ResearchGate</a>
    {% endif %}.
  </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
