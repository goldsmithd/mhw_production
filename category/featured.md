<div class="section-title">
    <h2><span>Featured v3</span></h2>
</div>

<div class="row listfeaturedtag">

{% for post in site.posts %}

    {% if post.featured  == true %}

        {% include featuredbox.html %}

    {% endif %}

{% endfor %}

</div>