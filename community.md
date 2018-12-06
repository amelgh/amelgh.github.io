---
layout: page
title: Community
description: Amel Ghouila's Community Activities
permalink: /community/
---

<img src="/images/TechnovationNationalPitch2017.jpg" alt="Technovation National Pitch, Tunisia 2017" style="width:80%;display:block;margin-left:auto;margin-right:auto">

<h4><p style="text-align: center;"><i>An overview of my community work in both<br /><a href="/community#womens-empowerment-activities">women's empowerment</a> and <a href="/community#open-science-activities">open science</a></i></p></h4>

***
***
<br>

### Women's Empowerment Activities

I am actively engaged in designing and conducting a variety of activities aiming to empower young girls and women. Here is a curated list of community activities I have been involved with:

{% for wags in site.data.womenandgirls %}
- **{{ wags.role }}**. *{{ wags.activity }}*. {{ wags.date }}
{% endfor %}

***
***
<br>

### Open Science Activities

{% for comm in site.data.community %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
