---
layout: default
permalink: /
---

<div class="row justify-content-center align-items-center p-4">
  <div class="col-lg-4 col-md-6 text-center mt-4">
    <!-- Fine Circle Responsive Image -->
    <div id="container" class="my-2">
      <div id="dummy"></div>
      <div id="element">
        <img src="{{ site.author.image }}" alt="{{ site.title }}" class="circle-image wow animated zoomIn" data-wow-delay=".1s">
      </div>
    </div>
  </div>
</div>
<div class="text-left wow animated slideInUp" data-wow-delay=".15s">
    <!-- <h1 class="display-6">THIS SITE IS CURRENTLY A WIP!</h1> -->
    <h1 class="display-4"> Hi! I'm Shivi, </h1>
    {% include about/summary_lead.html %}
    {% include about/summary.html %}
    <p>To learn more about my background, research experience, and game development projects, please visit the following links:</p>
    <ul>
      <li>My CV (<a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/assets/documents/Resumes/Academic/VATS_Shivi_CV.pdf">academia</a>, <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/assets/documents//Resumes/Tech/VATS_Shivi_CV.pdf">software engineering</a>, or <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/assets/documents/Resumes/GameDev/VATS_Shivi_CV.pdf">game development</a> oriented) and <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/about">more about me</a></li>
      <li><a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/projects">Game Projects</a></li>
      <li><a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/academic-work">Academic Work</a></li>
      <li><a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/other-work">Non-Game Projects</a></li>
      <li><a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="/blog">Blog</a></li>
    </ul>
    <p>You can reach me at <a class="link-underline link-underline-opacity-0 link-underline-opacity-75-hover" href="mailto:shivivats7@gmail.com">shivivats7@gmail.com</a>.</p>
    <h3>News</h3>
    {% include about/news.html %}
</div>