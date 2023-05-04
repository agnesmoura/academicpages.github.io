---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  Você pode encontrar meus trabalhos publicados no <u><a href="http://lattes.cnpq.br/2049370596015225">meu perfil do currículo Lattes</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
