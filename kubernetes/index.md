---
category: kubernetes
---
# K8S
{{ page.category }}

{% for category in site.categories %}
  {% if category[0] == page.category %}
## {{ category[0] }}
   {% for post category tag[1] %}
    [ {{ post.title }} ]( https://patrickA8S.github.io{{ post.url }} )
   {% endfor %}
  {% endif %}
{% endfor %}

