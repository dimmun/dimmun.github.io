---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ul>{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>


Publications
======
  <ul>{% for post in site.publications  reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% include base_path %}
Other
======
 <b>V.R. Munirov</b>, <i>Investigation of the interaction of non-uniformly charged macroparticles</i>, Master's thesis, Moscow Institute of Physics and Technology (2013)
[pdf]('/files/pdf/Munirov2013_dip_master_A4.pdf')
