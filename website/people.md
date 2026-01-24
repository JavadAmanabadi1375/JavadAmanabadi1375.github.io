---
layout: page
title: People
permalink: /people/
---

# People

{% for person in site.people %}
## {{ person.name }}
{{ person.role }}
[Profile →]({{ person.url }})
---
{% endfor %}
