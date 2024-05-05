---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
** Conference Publications **
* April 2024 **Teaching Assistant**, IIT Gandhinagar
 
** Posters **
* Course: Principles and Applications of Electrical Engineering
  * Instructor: Dr. Arup Lal Chakraborty, Professor, IIT Gandhinagar
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
