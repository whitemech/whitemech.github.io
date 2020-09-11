---
title: "WhiteMech - Media"
layout: textlay
excerpt: "Media"
sitemap: false
permalink: /media
---

# Media
{::nomarkdown}
<div class="row">
<div id="mediaid" class="col-sm-3">
<div class="card">
  <h5 class="card-header">Links</h5>
  <div class="card-body">
    <p class="card-text">
    {% for link in site.data.links %}
        <p class="text-justify">
        <a target="_blank" href="{{ link.url }}"><b>{{ link.title }}</b></a>
        </p>
    {% endfor %}
    </p>
  </div>
</div>
</div>
<div id="mediaid" class="col-sm-9">
<div class="card">
  <h5 class="card-header">Articles</h5>
  <div class="card-body">
    <ul>
    {% for article in site.data.media %}
        <li>
        <p class="text-justify">
        {{ article.date }}<br>
        <b>{{ article.title }}</b><br>
        {% for url in article.urls %}
            <a target="_blank" href="{{ url }}"><i class="material-icons-round">link</i></a>
        {% endfor %}
        </p>
        </li>
    {% endfor %}
    </ul>
  </div>
</div>    
</div>
</div>
{:/}
