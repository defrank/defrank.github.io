---
title: Portfolio
layout: default
---

Portfolio
---------

{% for proj in site.data.portfolio %}
### {% if proj.url %}[{{ proj.title }}]({{proj.url}}){% else %}{{ proj.title }}{% endif %}

| {{ proj.year }} | [{{ proj.repository.name}} Repository]({{ proj.repository.url }}) | 

![{{ proj.image.name }}]({{ proj.image.url }})

#### Description
{{ proj.description }}

#### Technology
{% for tech in proj.technologies %} * {{ tech }}
{% endfor %}

----
{% endfor %}
