---
category: kubernetes
date: 2021-01-01
---
# K8S
{% include long_date.html date=page.date %}:{{ page.category }}

{% for category in site.categories %}
  {% if category[0] == page.category %}
## {{ category[0] }}
   {% for post in category[1] %}
    [ {{ post.title }} ]( https://patrickA8S.github.io{{ post.url }} )
   {% endfor %}
  {% endif %}
{% endfor %}

