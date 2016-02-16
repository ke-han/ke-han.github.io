---
layout: page-fullwidth
show_meta: false
title: "Members"
subheadline: "Our core team"
header:
   title: Members and collaborators
   image_fullwidth: "banner2.jpg"
permalink: "/members/"
---
<div class="row">
    {% for member in site.data.members %}
    <div class="medium-3 columns">
        <section>
            <img src="/headshots/{{ member.picture }}.jpg" alt="" />

            <header>
                <h4>{{ member.name }} </h4>
            </header>
            <p> {{ member.bio }} </p>
        </section>
    
    </div>
    {% endfor %}
</div>
