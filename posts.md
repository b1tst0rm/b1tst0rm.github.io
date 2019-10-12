---
layout: default
comments: false
---
{% for post in site.posts %}
# [{{ post.title }}]({{ post.url }})
{{ post.date | date_to_long_string }}

---
{% endfor %}
