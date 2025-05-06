---
layout: archive
title: "Select Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap"><a href="https://scholar.google.com/citations?hl=en&user=B5Q8SkAAAAAJ">Here</a>'s my Google Scholar for a full list, but also check out my <a href="https://baylorfain.github.io/cv/">CV</a>.</div>
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
