---
layout: page-fullwidth
show_meta: false
title: "Invited Talks"
subheadline: "Our results"
header:
   title: Talks and Publications 
   image_fullwidth: "banner2.jpg"
permalink: "/publications/"
---
<div class="row">
<ol>
    {% for talk in site.data.talks %}
    <li>
    <em>{{ talk.title }}: </em>  {{ talk.details }}
    </li>
    {% endfor %}
</ol>
</div>

<h1> Publications in peer reviewed journals </h1>
<div class="row">
<ol>
    {% for paper in site.data.publications %}
    <li>
    <em>{{ paper.authors}}</em>, {{ paper.title }}, {{ paper.journal }}
    </li>
    {% endfor %}
</ol>
</div>
