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

[Download my CV as a PDF](#).

<p>You can reach me at <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="mailto:shivivats7@gmail.com">shivivats7@gmail.com</a>.</p>

<!-- 
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div> 
-->

<div class="mb-4">
    <h2> General Info </h2>
    <div class="row row-cols-1 row-cols-lg-3 mt-4">
        <div class="col">
        <h3>Languages</h3>
        <p>
        <strong>Hindi:</strong> C2 (Native) <br/>
        <strong>English:</strong> C2 (Fluent) <br/>
        <strong>German:</strong> A2-B1 (Intermediate)
        </p>
        </div>
        <div class="col">
        <h3>Tech Stack</h3>
        <p>
        Unity, C# <br/>
        Unreal Engine, C++, Blueprints <br/>
        Android, JAVA <br/>
        Python, NumPy, Flask <br/>
        MRTK2, ARCore <br/>
        </p>
        </div>
        <div class="col">
        <h3>Socials</h3>
        <p>
        <i class="fab fa-brands fa-linkedin"></i> <a>Shivi Vats</a><br/>
        <i class="fab fa-brands fa-github"></i> <a>shivivats</a><br/>
        <i class="fab fa-brands fa-github"></i> <a>shivivats-aau</a><br/>
        <i class="fab fa-brands fa-itch-io"></i> <a>zarroc</a>
        </p>
        </div>
    </div>
</div>

<div class="row">
<h2> Work Experience and Education </h2>
{% include about/timeline.html %}
</div>