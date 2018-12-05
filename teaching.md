---
layout: page
title: Presentations
description: Amel Ghouila's teaching experience
permalink: /teaching/
---

***
***
<br>




{% for pres in site.data.teaching %}
  {% if pres.role == null %}
- *{{ pres.courseTitle }}*. <u>{{ pres.courseVenue }}</u>. {{ pres.courseLocation }}. {{ pres.courseDate }}
  {% else %}
- **{{ pres.role }}**. *{{ pres.courseTitle }}*. <u>{{ pres.courseVenue }}</u>. {{ pres.courseLocation }}. {{ pres.courseDate }}
  {% endif %}
{% endfor %}

***
***

