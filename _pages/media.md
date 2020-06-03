---
title: "WhiteMech - Media"
layout: textlay
excerpt: "Media"
sitemap: false
permalink: /media
---

# Media

<ul>
{% for article in site.data.media %}
<li>
<p class="text-justify">
{{ article.date }}<br>
<b>{{ article.title }}</b><br>
<a target="_blank" href="{{ article.url }}"><i class="material-icons-round">link</i></a>
</p>
</li>
{% endfor %}
</ul>