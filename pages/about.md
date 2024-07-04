---
layout: page
title: About
permalink: /about/
weight: 5
---

<h1 class="display-6">THIS SITE IS CURRENTLY A WIP!</h1>
# **About Me**
<div class="row">
    <div class="lead">Hi! I am <strong>{{ site.author.name }}</strong> :wave:,<br></div>
    {% include summary.html %}
</div>

<!-- 
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div> 
-->

<div class="row">
<h2> Work Experience and Education </h2>
</div>

<div class="row">
{% include about/timeline.html %}
</div>