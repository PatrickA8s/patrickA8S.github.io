---
category: kubernetes
---
# K8S
{{ page.category }}

{% for category in site.categories %}
  {% if category[0] == page.category %}
   ## {{ page.category }}
   {% for post in tag[1] %}
    [ {{ post.title }} ]( https://patrickA8S.github.io{{ post.url }} )
   {% endfor %}
  {% endif %}
{% endfor %}

