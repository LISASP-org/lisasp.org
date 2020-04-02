---
layout: page
title: Development
permalink: /development/
---

# Development

Welcome to the {{ site.domain }} development pages. Here you can quickly jump to a 
particular project. The projects are mostly independent und unrelated to {{ site.domain }} 
and listed because their focus.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
