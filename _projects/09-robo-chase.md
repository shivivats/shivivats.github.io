---
name: Robo Chase
description: A local two-player split-screen retro platformer where the cop player tries to catch the robot player.
image: /assets/images/games/robochase/robo-chase-featured.png
tools: [C#, Unity, 2D, Local Multiplayer]
---

# Robo Chase


Robo Chase is a **local two-player retro platformer**, with one player playing as a cop chasing to catch the other player playing as a robot. Both players have to avoid a wall of laser coming at them, among other obstacles and traps. It’s played on a split screen and the game ends when either player dies, the cop catches the robot, or the robot makes it to the end of the level.

The game was made as an entry to the [Retro Platformer Jam](https://itch.io/jam/retro-platformer-jam) held in December 2018, and we ended up getting 1st place in the “Technical” category. It was built using the **Unity3D** engine and written in **C#**. I worked with a friend on it and while he took up the role of artist and programmer, I **mainly programmed**. We implemented **two levels** (an easy and a difficult one), chosen at random for the players. The game can also be played in single-player mode with the players as the cop trying to catch the robot.

The game can be found at [zarroc.itch.io/robo-chase](https://zarroc.itch.io/robo-chase). Here are some screenshots and a gameplay sample:


<div id="roboChaseCarousel" class="carousel slide" data-bs-theme="dark">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#roboChaseCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#roboChaseCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#roboChaseCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#roboChaseCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/games/robochase/robo-chase-featured.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/robochase/robochase-1.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/robochase/robochase-2.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/robochase/robochase-3.png" class="d-block w-75" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#roboChaseCarousel" data-bs-slide="prev"  data-bs-theme="dark">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#roboChaseCarousel" data-bs-slide="next"  data-bs-theme="dark">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="text-center">
    <p>Robo Chase Screenshots</p>
</div>


<div class="row">
    <div class="col-sm mt-3 ratio ratio-16x9 center-block">
        <iframe class="embed-responsive-item" width="640" height="360" src="https://www.youtube.com/embed/pC7kbHzRbIA?si=E2w1VmgWXESnpd6s" allowfullscreen class="w-80 p-3"></iframe>
    </div>
</div>
<div class="text-center">
    Robo Chase Gameplay Sample
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the projects home by clicking [here](/projects).*


## Background

I had just moved to Austria a few weeks before. Coming from half the world away, I knew no one and barely spoke the language. However I made a friend quite early on and we decided that what better way to get to know each other than to work on a game together! We picked that [game jam](https://itch.io/jam/retro-platformer-jam) in particular as it fell on the only free weekend we had before the game jam held at our university. We were already planning to participate in the [university’s game jam](https://itch.io/jam/2nd-winter-game-jam) as a team so we wanted to get some experience working together beforehand.

## Development Process

We both had prior programming experience and experience with Unity, so we decided to make things a bit harder for ourselves by trying to program a two-player game, as we had yet to do that before. We were also excited that the jam dictated the game should be played with a controller since, at the time, we didn’t know how to configure Unity to use a controller, and we wanted to learn.

The jam’s theme was Cyberpunk. So we decided to go with the classic “robot gone rogue” setting, with a cop trying to catch it. The game was a lot of firsts for us, and we scrapped quite a few features that we had planned simply because we didn’t estimate how long it would take for certain core features to be implemented. We also intended for the game to be two-player only, but we soon realised that the person rating the game would be playing alone, so we implemented a single-player mode, which wasn’t part of our initial plan.

The game ended up being rushed, but we implemented the core features, and the final product had the essence we wanted.

## What did I learn?

As with most projects I make, I challenge myself to try something I haven't tried before. For this, it was multiplayer, audio controller, and teamwork. I experienced what it was like having to match another person's pace and meet their expectations. I've learnt from it and applied it to other projects. It was also one of my first times working with Unity3D and C#, and since then, I've grown much more confident in using those tools.

## Final Thoughts

Ultimately, the game holds a special place in my heart as sitting together and gaming with your friends is one of life's best experiences, and I was glad we could make a game that fits the dying couch multiplayer genre. Even though it was an unfinished product, it was still fun to play with a friend!

<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>