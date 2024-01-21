---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

## Conference and Workshop Talks


<div class="jumbotron">
{% for publi in site.data.conference_talks %}
- <strong>{{ publi.title }}</strong> <br/> 
 <i>{{ publi.conf }}</i> ({{ publi.year }}) <br/>
{% endfor %}
</div>

