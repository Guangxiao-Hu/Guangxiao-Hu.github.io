---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journal Articles
[J] **Hu, G.**, Feng, K., & Sun, L. (2023). [Multiscale Analysis of the Relationship between Toxic Chemical Hazard Risks and Racial/Ethnic and Socioeconomic Groups in Texas, USA](https://pubs.acs.org/doi/abs/10.1021/acs.est.2c04302). Environmental Science & Technology, 57(5), 2019-2030. 

[J]  **Hu, G.**, Feng, K., Sun, L., & Baiocchi, G. (2023). [Tracing toxic chemical releases embodied in US interstate trade and their unequal distribution](https://www.sciencedirect.com/science/article/pii/S0160412022006080). Environment international, 171, 107681. 

[J] **Hu, G.**, Hamovit, N., Croft, K., Roberts, J. D., & Niemeier, D. (2022). [Assessing inequities underlying racial disparities of COVID-19 mortality in Louisiana parishes](https://www.pnas.org/doi/abs/10.1073/pnas.2123533119). Proceedings of the National Academy of Sciences, 119(27), e2123533119.

## Conference Papers



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
