---
layout: page
title: Publications
description: Amel Ghouila's publications
permalink: /publications/
---

***
***
<br>

### Publications (rev. chronological order)

{% for pub in site.data.publications %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}

***
***

