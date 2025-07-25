---
name: Stranded
description: A 2D space-themed platformer in which the player slings themselves around planes to get to their spaceship.
image: /assets/images/games/stranded/stranded-featured.png
tools: [C#, Unity, 2D]
featured: false
---

# Stranded

Stranded is a **2D platformer** where the player slings themselves around planets to get to their spaceship. It was developed for [Blackthornprod Game Jam #2](https://itch.io/jam/blackthornprodgamejam2), held in March 2019. The game contains 3 levels, each on a different planet with varying level of difficulty, with the first planet acting as a tutorial level.

The game was built using the **Unity3D** engine and written in **C#**. I worked in a **team of five** on this, as a **gameplay programmer**, including the **slinging functionality** which was inspired by the bash functionality in Ori and the Blind Forest.

The game can be found at [geist-191.itch.io/stranded](https://geist-191.itch.io/stranded), and here’s a gameplay sample:

<div class="row">
    <div class="col-sm mt-3 ratio ratio-16x9 center-block">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/nDd2Sn33yc4" title="Stranded Gameplay Sample" allowfullscreen class="w-80 p-3"></iframe>
    </div>
</div>
<div class="text-center">
    Stranded Gameplay Sample
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*


## Background

[Blackthornprod](https://twitter.com/NoaCalice) is a YouTuber that my friends and I liked to watch, so when we found out that they were planning to host a [game jam](https://itch.io/jam/blackthornprodgamejam2), we decided we wanted to participate. Since all 5 of us wanted to participate, we decided to do it together. However, we soon realised that five people without much teamwork experience don't work well together.

## Development Process

The jam's theme was "Mini Planets". As with other game jams, we brainstormed ideas individually and pitched them, and the most liked ones were developed together. Initially, we settled on making a platformer where players jumped from planet to planet, like in Super Mario Galaxy. However, that wasn't the case since some team members had different ideas, and we realised that late into the development process. So, we made only three reasonably large-sized planets instead of small planets that the player could quickly traverse.

There was a lot of miscommunication, but we knew we wanted obstacles, so I worked on making all the mechanics for the player and the obstacles, including the inwards gravity and the slinging. At the same time, I sat with our level designer to figure out how exactly he wanted the obstacles to work. The two of us were in sync and managed to make that part of the game well.

However, through the development process, due to miscommunication regarding how others' code worked, we had quite a few bugs that required more effort than usual to be solved. Even though we solved most of them, the audio system still needed to be fixed since it was designed last minute.

This was my first game in which we had a dedicated artist, so our game's visual aspect attracted quite a few players and was generally well-received.


## Final Thoughts. What did I learn?

Working in a team is more complicated than it seems. This was the most stressful game I had yet made, and that's a shame, considering I quite liked the concept. If I were to work in a team of >3 independent devs again, I would push for the team to have dedicated roles for management and ensure everyone is in sync regarding the game's design and development. I have worked in groups of four since, and the projects have gone much more smoothly when we ensured that everyone knew what the vision for the project was before we started the bulk of the development.


<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>