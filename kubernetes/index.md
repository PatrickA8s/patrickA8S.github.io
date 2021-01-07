---
category: kubernetes
---
K8S
{{ page.category }}

{% for category in site.categories %}
  {% if category[0] == page.category %}
    {{ page.category }}
  {% endif %}
{% endfor %}

