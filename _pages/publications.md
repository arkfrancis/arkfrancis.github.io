---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page is under construction. A list of my publications can be found <u><a href="http://staff.scem.uws.edu.au/~andrew/pubs/index.html">here</a></u>, or on <u><a href="https://scholar.google.com.au/citations?user=zGAdnBkAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
