---
title: "WhiteMech - People"
layout: gridlay
excerpt: "WhiteMech: People"
sitemap: false
permalink: /people
---

<div class="alert alert-danger">
We are currently looking for new PhD students, Postdocs, and Master students to join the team. <a href="{{ site.url }}{{ site.baseurl }}/hiring" class="alert-link">See Hiring!</a>
</div>

# Faculty
{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row mt-4">
{% endif %}

{::nomarkdown} 
<div class="card shadow mb-3 ml-3" style="max-width: 545px;">
<div class="row">
<div class="col-md-4">
<img src="{{ site.url }}{{ site.baseurl }}/static/images/faculty/{{ member.photo }}" class="card-img" alt="...">
</div>
<div class="col-md-8">
<div class="card-body">
<h5 class="card-title">{{ member.name }}</h5>
<p class="card-text mb-4">{{ member.info }}</p>

{% if member.email %}
<a target="_blank" href="mailto:{{ member.email }}"><i class="material-icons-outlined">alternate_email</i></a>
{% endif %}
{% if member.website %}
<a target="_blank" href="{{ member.website }}"><i class="material-icons-outlined">perm_identity</i></a>
{% endif %}
{% if member.scholar %}
<a target="_blank" href="{{ member.scholar }}"><i class="material-icons-outlined">science</i></a>
{% endif %}

</div>
</div>
</div>
</div>
{:/}  
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Postdocs
{% assign number_printed = 0 %}
{% for member in site.data.postdocs %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row  mt-4">
{% endif %}

{::nomarkdown} 
<div class="card shadow mb-3 ml-3" style="max-width: 545px;">
<div class="row">
<div class="col-md-4">
<img src="{{ site.url }}{{ site.baseurl }}/static/images/postdocs/{{ member.photo }}" class="card-img" alt="...">
</div>
<div class="col-md-8">
<div class="card-body">
<h5 class="card-title">{{ member.name }}</h5>
<p class="card-text mb-4">{{ member.info }}</p>

{% if member.email %}
<a target="_blank" href="mailto:{{ member.email }}"><i class="material-icons-outlined">alternate_email</i></a>
{% endif %}
{% if member.website %}
<a target="_blank" href="{{ member.website }}"><i class="material-icons-outlined">perm_identity</i></a>
{% endif %}
{% if member.scholar %}
<a target="_blank" href="{{ member.scholar }}"><i class="material-icons-outlined">science</i></a>
{% endif %}
{% if member.linkedin %}
<a target="_blank" href="{{ member.linkedin }}"><i class="material-icons-round">link</i></a>
{% endif %}
{% if member.github %}
<a target="_blank" href="{{ member.github }}"><i class="material-icons-round">code</i></a>
{% endif %}

</div>
</div>
</div>
</div>
{:/}  
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# PhD Students

{% assign number_printed = 0 %}
{% for member in site.data.phds %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row  mt-4">
{% endif %}

{::nomarkdown} 
<div class="card shadow mb-3 ml-3" style="width: 545px;">
<div class="row">
<div class="col-md-4">
<img src="{{ site.url }}{{ site.baseurl }}/static/images/phds/{{ member.photo }}" class="card-img" alt="...">
</div>
<div class="col-md-8">
<div class="card-body">
<h5 class="card-title">{{ member.name }}</h5>
<p class="card-text mb-4">{{ member.info }}</p>

{% if member.email %}
<a target="_blank" href="mailto:{{ member.email }}"><i class="material-icons-outlined">alternate_email</i></a>
{% endif %}
{% if member.website %}
<a target="_blank" href="{{ member.website }}"><i class="material-icons-outlined">perm_identity</i></a>
{% endif %}
{% if member.scholar %}
<a target="_blank" href="{{ member.scholar }}"><i class="material-icons-outlined">science</i></a>
{% endif %}
{% if member.linkedin %}
<a target="_blank" href="{{ member.linkedin }}"><i class="material-icons-round">link</i></a>
{% endif %}
{% if member.github %}
<a target="_blank" href="{{ member.github }}"><i class="material-icons-round">code</i></a>
{% endif %}

</div>
</div>
</div>
</div>
{:/}  
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Administration
{% assign number_printed = 0 %}
{% for member in site.data.admin_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row mt-4">
{% endif %}

{::nomarkdown} 
<div class="card shadow mb-3 ml-3" style="width: 545px;">
<div class="row">
<div class="col-md-4">
<img src="{{ site.url }}{{ site.baseurl }}/static/images/admin/{{ member.photo }}" class="card-img" alt="...">
</div>
<div class="col-md-8">
<div class="card-body">
<h5 class="card-title">{{ member.name }}</h5>
<p class="card-text mb-4">{{ member.info }}</p>

{% if member.email %}
<a target="_blank" href="mailto:{{ member.email }}"><i class="material-icons-outlined">alternate_email</i></a>
{% endif %}
{% if member.website %}
<a target="_blank" href="{{ member.website }}"><i class="material-icons-outlined">perm_identity</i></a>
{% endif %}
{% if member.scholar %}
<a target="_blank" href="{{ member.scholar }}"><i class="material-icons-outlined">science</i></a>
{% endif %}
{% if member.linkedin %}
<a target="_blank" href="{{ member.linkedin }}"><i class="material-icons-round">link</i></a>
{% endif %}
{% if member.github %}
<a target="_blank" href="{{ member.github }}"><i class="material-icons-round">code</i></a>
{% endif %}

</div>
</div>
</div>
</div>
{:/}  
{% endfor %}
