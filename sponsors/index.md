---
layout: default
title: Sponsors
---
{% for sponsor in site.data.sponsors %}
{% if sponsor.url %}
[{{ sponsor.name }}]({{ sponsor.url }})
{% else %}
{{ sponsor.name }}
{% endif %}
{% endfor %}
