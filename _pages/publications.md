---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<br>
A detailed list of my articles can be found on [Google Scholar](https://scholar.google.com/citations?user=j8AtLDYAAAAJ&hl=en&oi=ao)<br>
<br>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
