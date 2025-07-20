---
name: Breakup Bonanza&#58; A Dumping Simulator
description: A visual novel where the player has to navigate dialogue choices to successfully break-up with their toxic partners.
image: /assets/images/games/breakupbonanza/featured.png
tools: [Python, 2D]
featured: false
---

# Breakup Bonanza: A Dumping Simulator

Breakup Bonanza is a **2D visual novel** built for [Klagenfurt 7th Winter Klujam](https://itch.io/jam/7th-winter-game-jam), held in December 2023. The game explores the concept of toxic masculinity, challenging the player to navigate breakups with three distinct partners, carefully choosing dialogue options to avoid damaging the partners'  “fragile masculinity.”

The game was built using **RenPy**, written in **Python**, and built by a **team of eight**, although only six members were actively involved throughout the jam. I worked as the **lead programmer** primarily responsible for implementing the core gameplay features, including the gameplay tree and the “fragile masculinity” bar system – which I also designed using Photoshop. The remaining team members contributed as background artists, character artists, writer, and BGM designers.

The game can be found at [tan-tan.itch.io/breakup-bonanza](https://tan-tan.itch.io/breakup-bonanza), and here’s some screenshots:

<div id="breakupbonanzaCarousel" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="4" aria-label="Slide 5"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="5" aria-label="Slide 6"></button>
    <button type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide-to="6" aria-label="Slide 7"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/games/breakupbonanza/BwGR4.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/4MVCKH.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/Bsi1MM.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/i1vfUK.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/MdMHTl.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/pt1oeP.png" class="d-block w-75" alt="...">
    </div>
     <div class="carousel-item">
      <img src="/assets/images/games/breakupbonanza/ywSSrH.png" class="d-block w-75" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide="prev" data-bs-theme="dark">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#breakupbonanzaCarousel" data-bs-slide="next" data-bs-theme="dark">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="text-center">
    Breakup Bonanza Screenshots
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*


## Background
I hadn't made a game since 2019,  and the University winter game jam presented an opportunity to return to the hobby. I also, after a long time, had a friend group with people who were interested in gamedev. Thus, we all decided that we wanted to work together on the game jam, if our ideas aligned. And lo and behold, once we heard that the main topic was "Caution: Fragile", our first thought went towards fragile masculinity.

Initially, I wanted to get into a more programming-heavy game idea, to also be able to show-off my programming skills by putting the game on my portfolio afterwards. However, I am very happy with how this game turned out. I was still able to implement some custom functionality into [RenPy](https://www.renpy.org/), and in the end I also have a game that I am very proud to show off on my portfolio since it focuses on an issue I care about a lot and is also very prominent in our society.


## Development Process

The process was a bit convoluted at first, with 8 people being in the team overall. However, only about six of us were available to work on the game for most of the time. I initially floated the idea to program a custom Visual Novel engine in Unity, but thankfully, we soon realised that it would be a lot better for a game jam to just go with an existing engine.

RenPy's documentation was easy to follow, and soon I had the barebones of our game set up, such as the fragility functionality, and the various scenes for the different partners. While the rest of the team worked on the writing, the art, and the music, I looked at the list of tasks and decided to work on a visual fragility bar. It took me some time, but I'm quite alright with Photoshop.

The game was overall not that hard to make from a programmer's perspective, but it was exciting to work with a new framework nonetheless.

## Final Thoughts.

This game represents several firsts for me. It represents my first game after a long (unintentional) hiatus from game development. It represents my first project with a group of friends that I hold very dear to me. And it represents my first game that can be somewhat considered to be in the direction of activism. I've always wanted to be more active, to raise awareness about the many issues that plague our society. And I finally found a medium that worked for me. 


<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>