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


<h2>Journal Articles</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conferences</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Patents</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'patent' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
