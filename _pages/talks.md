---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

## Conference Presentations

[4] **Hu, G.**, Feng, K., Sun, L. 2023, May. Multiscale Analysis of the Relationship between Toxic Chemical Hazard Risks and Racial/Ethnic and Socioeconomic Groups in Texas, USA. Poster presentation at 2023 BSOS Resilience Research Showcase. 

[3] **Hu, G.**, Feng, K., Sun, L. 2023, March. Is pollution inequality improved or worsen over time? Spatiotemporal heterogeneity of the impact of racial disparities and socioeconomic development on toxic risk. Oral presentation at 2023 AAG Annual Meeting.

[2] **Hu, G.**, 2021, December. Pollution Inequality of Toxic Chemical Release Embodied in Final Demand by States and Income Groups in the US. Poster Presentation at AGU Fall Meeting (GC25G-0729).

[1] **Hu, G.**, Feng, K. 2021, June. Pollution inequality of toxic chemical release embodied in interregional trade in the US”. Oral presentation at International Industrial Ecology Day 2021. 

## Invited talks
[5] **Hu, G.**, (Februray 2026). Building an interdisciplinary research pathway: from PhD training to the faculty job market, ICS Lab meeting, Integrated Coastal Programs, East Carolina University, USA.

[4] **Hu, G.**, (Februray 2026). Revealing spatiotemporal variations in environmental inequality, Lunch and Learn Series, Department of Public Health, East Carolina University, USA.

[3] **Hu, G.**, (November 2025). GIS application in visualizing environmental inequality, GIS Day, East Carolina University, USA.

[2] **Hu, G.**, (December 25, 2023). "Revealing variations in environmental inequality," invited by Weihai Institute for Interdisciplinary Research, Shandong University, China.

[1] **Hu, G.**, Jiehong Lou, (November 7, 2023). "Quantify the Economy-wide Employment effect from Coal-fired Power Plants - Two Different Cases China and the United States", at Center for Sustainability, Univerisity of Maryland, USA.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
