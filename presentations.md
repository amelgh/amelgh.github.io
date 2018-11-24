---
layout: page
title: Presentations
description: Amel Ghouila's presentations
permalink: /presentations/
---

***
***
<br>


### Presentations (rev. chronological order)

{% for pres in site.data.presentations %}
  {% if pres.role == null %}
- *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% else %}
- **{{ pres.role }}**. *{{ pres.talkTitle }}*. <u>{{ pres.talkVenue }}</u>. {{ pres.talkLocation }}. {{ pres.talkDate }}
  {% endif %}
{% endfor %}

***
***

