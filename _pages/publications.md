---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journal Articles
[J] **Hu, G.**, Feng, K., & Sun, L. (2023). Multiscale Analysis of the Relationship between Toxic Chemical Hazard Risks and Racial/Ethnic and Socioeconomic Groups in Texas, USA. Environmental Science & Technology, 57(5), 2019-2030. (https://pubs.acs.org/doi/abs/10.1021/acs.est.2c04302)


## Conference Papers



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
