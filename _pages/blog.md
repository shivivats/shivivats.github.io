---
layout: default
title: Blog Home
permalink: /blog
comments: false
---


<!-- Featured
================================================== -->
<section class="featured-posts">
    <div class="section-title">
        <h2><span>Featured Posts</span></h2>
    </div>
    <div class="row">

    {% for post in site.posts %}

    {% if post.path contains "blog" %}

        {% if post.featured == true %}

            {% include featuredbox.html %}

        {% endif %}
    
    {% endif %}

    {% endfor %}

    </div>
</section>

<!-- Posts Index
================================================== -->
<section class="recent-posts">

    <div class="section-title">

        <h2><span>All Posts</span></h2>

    </div>

    <div class="row listrecent">

        {% for post in site.posts %}

             {% if post.path contains "blog" %}

                {% include postbox.html %}

            {% endif %}

        {% endfor %}

    </div>

</section>

<!-- Pagination
==================================================
<div class="bottompagination">
<div class="pointerup"><i class="fa fa-caret-up"></i></div>
<span class="navigation" role="navigation">
    {% include pagination.html %}
</span>
</div>
 -->