---
layout: page
title: Teaching
description: Amel Ghouila's teaching experience
permalink: /teaching/
---

***
***
<br>

I have been involved in organizing a number of bioinformatics and data science courses as well as designing collaborative peer learning activites.  I have also been invited to teach in a variety of international data science training activities. 
See below for a selection of courses, workshops, and hackathons. 

{% for teach in site.data.teaching %}
  {% if teach.role == null %}
- *{{ teach.courseTitle }}*. <u>{{ teach.courseVenue }}</u>. {{ teach.courseLocation }}. {{ teach.courseDate }}
  {% else %}
- **{{ teach.role }}**. *{{ teach.courseTitle }}*. <u>{{ teach.courseVenue }}</u>. {{ teach.courseLocation }}. {{ teach.courseDate }}
  {% endif %}
{% endfor %}

***
***

