---
name: Watermelon Game
description: A 2D mobile clone of the Suika game made alone as a way to learn Godot.
image: /assets/images/games/watermelongame/featured.png
tools: [Godot, 2D, Mobile]
featured: true
---

# Watermelon Game

<i class="fab fa-github fa-1x"></i> [shivivats/Watermelon-game](http://github.com/shivivats/Watermelon-game)

Watermelon Game is a **2D mobile** clone of the [Suika Game](https://en.wikipedia.org/wiki/Suika_Game) game using **Godot**. I built it in September 2024 for my girlfriend, who had at the time found herself addicted to the game whenever it (or rather, yet another clone of it) showed up on Duolingo ads...

As mentioned before, the game is built using **Godot**. was my first time using the engine, and I decided to go with something relatively easy to learn the ropes. I built the whole game myself, using some free to use assets (list in the GitHub Readme) as well as the assets from the original Suika game.

The gameplay is the same as the original Suika game, with the player seeing the box, their current score, and the fruit that's next up. The biggest thing missing from the UI is the cycle that shows the player which fruit two of the same fruit turn into.

The game is not available to play online, but here are a GIF and some screenshots from the game:

<div id="watermelongameCarousel" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#watermelongameCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#watermelongameCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#watermelongameCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#watermelongameCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#watermelongameCarousel" data-bs-slide-to="4" aria-label="Slide 5"></button>
  </div>
  <div class="carousel-inner">
     <div class="carousel-item active">
      <img src="/assets/images/games/watermelongame/watermelongame.gif" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/watermelongame/screenshot1.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/watermelongame/screenshot2.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/watermelongame/screenshot4.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/watermelongame/screenshot6.png" class="d-block w-75" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#watermelongameCarousel" data-bs-slide="prev" data-bs-theme="dark">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#watermelongameCarousel" data-bs-slide="next" data-bs-theme="dark">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="text-center">
    Watermelon Game Screenshots
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*


## Background

I had wanted to learn Godot for a long time, but I found that going through tutorials, even really exhaustive ones such as this [11.5 hour video](https://www.youtube.com/watch?v=nAh_Kx5Zh5Q), was neither motivating nor interesting enough for me. Thus, I decided to focus on just getting some [quick](https://www.youtube.com/watch?v=LOhfqjmasi0) [introductions](https://www.youtube.com/watch?v=e1zJS31tr88) to the engine and working on a game small enough to not overwhelm me.

I first thought of remaking a classic such as Tetris or Breakout but my girlfriend's addiction to a clone of the Suika game, and her dismay when the ad gameplay would eventually force her to download the actual app, motivated me enough to decide to go ahead with this idea.

## Development Process

The development process was a bit slow, and very iterative, as I had expected when developing a game while still learning the engine.

GDScript wasn't that big of a hassle to get used to, since its a lot like Python, and I was absolutely blown away by the instant compilation times. However, the Godot UI was a bit too convoluted an cramped for my taste, and I would've liked it to be more spacious by default. I also didn't want to get into customizing the UI of the engine itself already as part of my first project.

The GitHub repository contains a list of some of the Godot "features" I used that I  deemed worth documenting. It also contains some anecdotes from the development process. I would refer you there for more info.


## Final Thoughts.

Outside of a few bugs that can be chalked up to not being familiar with the engine, the development process was quite pleasant. I liked how the engine flows, and I would like to work with it again. There's a To-Do list on the GH Readme as well, but I dont know if I'll ever get to checking those items off.

However, I can imagine myself using Godot for yet another, perhaps more complicated, mobile game project for whichever game my girlfriend is next addicted to...


<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>