---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Work in progress 

Baudot, F.-O. Impact of benzodiazepine use on the risk of occupational accident. [ERUDITE Working Paper] [https://erudite.univ-paris-est.fr/fileadmin/redaction/ERUDITE/Documents_de_travail/Documents_de_2022/WP_ERUDITE_02_2022-1.pdf]

Barnay, T., Baudot, F.-O. Work accident effect on the risk of benzodiazepine use and overuse. [ERUDITE Working Paper] [https://erudite.univ-paris-est.fr/fileadmin/redaction/ERUDITE/Documents_de_travail/Documents_de_2020/WP_ERUDITE_09_2020.pdf]

# Publications in peer-reviewed journals

Baudot, F.-O., Aguade, A. S., Barnay, T., Gastaldi-Menager, C., & Fagot-Campagna, A. (2018). Impact of type 2 diabetes on health expenditure: estimation based on individual administrative data. The European Journal of Health Economics, 20(5), 657-668. [link] [https://link.springer.com/article/10.1007/s10198-018-1024-9]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
