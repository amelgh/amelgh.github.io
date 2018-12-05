---
layout: page
title: Community
description: Amel Ghouila's Community Activities
permalink: /community/
---

***
***
<br>

I am committed to designing and running different activities aiming to empower young girls and women and I am also an active participant in the open science community. Here is a list of selected community activities I have been involved with:

### Women and girls empowrement activities



### Open science activities

{% for comm in site.data.community %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
