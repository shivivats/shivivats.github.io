---
layout: page
title: About
permalink: /about/
weight: 5
---

<!-- <h1 class="display-6">THIS SITE IS CURRENTLY A WIP!</h1> -->
# **About Me**
<div class="row">
    <div class="lead">Hi! I am <strong>{{ site.author.name }}</strong> :wave:,<br></div>
    {% include about/summary.html %}
</div>

Please [download my CV as a PDF](/assets/documents/Shivi_CV.pdf) or continue reading this page for more information.

<p>You can reach me at <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="mailto:shivivats7@gmail.com">shivivats7@gmail.com</a>.</p>

<!-- 
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div> 
-->

{% include about/stats.html %}

<div class="row">
<h2 class="pb-2 border-bottom"> Work Experience and Education </h2>
{% include about/timeline.html %}
</div>

<div class="row">
<h2 class="pb-2 border-bottom"> Publications </h2>
{% include about/publications.html %}
</div>