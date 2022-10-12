---
title: "WhiteMech - Gallery"
layout: gridlay
excerpt: "WhiteMech: Gallery"
sitemap: false
permalink: /gallery
---

{::nomarkdown}
<h1 class="mb-4">Gallery</h1>
<hr class="my-4">
{% for gallery in site.data.gallery %}
    <h2 id="ijcai-22">{{ gallery.name }}</h2>
    <div id="carousel-{{ gallery.folder }}" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        {% assign counter = 0 %}
        {% for image in site.static_files %}
            {% assign path = 'images/gallery/' | append: gallery.folder %}
            {% if image.path contains path %}
                {% if counter == 0 %}
                    <li data-target="#carousel-{{ gallery.folder }}" data-slide-to="{{ counter }}" class="active"></li>
                {% else %}
                    <li data-target="#carousel-{{ gallery.folder }}" data-slide-to="{{ counter }}"></li>
                {% endif %}
                {% assign counter = counter | plus: 1 %}
            {% endif %}
        {% endfor %}
    </ol>
    <div class="carousel-inner">
        {% assign counter = 0 %}
        {% for image in site.static_files %}
            {% assign path = 'images/gallery/' | append: gallery.folder %}
            {% if image.path contains path %}
                {% if counter == 0 %}
                    <div class="carousel-item active">
                    <img src="{{ site.baseurl }}{{ image.path }}" class="d-block w-100" alt="...">
                </div>
                {% else %}
                    <div class="carousel-item">
                    <img src="{{ site.baseurl }}{{ image.path }}" class="d-block w-100" alt="...">
                </div>
                {% endif %}
                {% assign counter = counter | plus: 1 %}
            {% endif %}
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carousel-ijcai22" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carousel-ijcai22" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
    </div>
    <hr class="my-4">
{% endfor %}
{:/}
