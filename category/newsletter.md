---
layout: default
disqus: true
archive: false
categories: [ advert ]
layout: default
title: Newsletter
---

<!-- Advert Posts
================================================== -->
<section class="advert-posts">

    <div class="section-title">
        <h2><span>NewsLetter v3</span></h2>
    </div>

    <div class="row listfeaturedtag">

    {% for post in site.posts %}

        {% if post.newsletter  == true %}

            {% include featuredbox.html %}

        {% endif %}

    {% endfor %}

    </div>

</section>

