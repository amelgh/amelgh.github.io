---
layout: page
title: Presentations
description: Amel Ghouila's teaching experience
permalink: /teaching/
---

***
***
<br>

I have been involved in organizing a number of Bioinformatics and data analysis courses and  designing collaborative peer learning activites.  I have also been invited to teach in a number of international data analysis trainings. 
See below for a selection of courses and hackathons. 

{% for pres in site.data.teaching %}
  {% if pres.role == null %}
- *{{ pres.courseTitle }}*. <u>{{ pres.courseVenue }}</u>. {{ pres.courseLocation }}. {{ pres.courseDate }}
  {% else %}
- **{{ pres.role }}**. *{{ pres.courseTitle }}*. <u>{{ pres.courseVenue }}</u>. {{ pres.courseLocation }}. {{ pres.courseDate }}
  {% endif %}
{% endfor %}

***
***

