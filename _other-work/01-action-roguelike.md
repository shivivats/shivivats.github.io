---
name: Action Roguelike
description: A 3D barebones for an action roguelike game made in Unreal Engine 4/5 and C++ following a course 
image: /assets/images/
tools: [Unreal Engine, 3D, CPP]
---

# Action Roguelike

This is the barebones for a 3D action roguelike game developed by following Tom Looman's [Professional Game Development in C++ and Unreal Engine](https://courses.tomlooman.com/p/unrealengine-cpp). The course has taught me a great deal and helped me get started with Unreal Engine 4 and 5 (I began with UE4 and later switched to UE5 upon its release).

The course has provided me with a good base-level understanding of how the engine is designed and the workflow that developers must follow to utilize it effectively. It has also made me realize that Unreal Engine is designed for interdisciplinary teams, and working on the engine alone is a big task, considering the diversity of implementation of various systems in the engine.

Overall, I am very satisfied with the engine and eager to learn more, despite the daunting task of mastering all its aspects. Working full-time and finding some time to do this course on the side has slowed my progress, but I am determined to complete it soon to gain a better understanding of implementing multiplayer, which is the final part of the course remaining for me.
<!-- (I already have a basic understanding of multiplayer in Unreal Engine; please see [my other post]().) -->


Some functionalities implemented in the game are:

- Imported and set up a Paragon character mesh and animations, and refactored it to fit this game's custom player controller.
- Configured third-person character movement, including implementing animation blendspaces for smooth transitions
- Implemented character attacks, including a basic projectile and a "black hole" attack that draws in nearby physics-enabled actors
- Implemented a teleportation ability for the character, using raycasting to determine a feasible destination for the teleport
- Added a modular interaction functionality via interfaces and components
- Designed and implemented basic UMG widgets, and some basic animations such as health bar zoom in/out opon damage taken
- Implemented basic flashing materials
- Added sound effects to basic gameplay such as movement, projectiles, damage, etc...
- Implemented enemy AI using Behaviour Trees and EQS
    - The AI attempts to reach a safe distance from the player before shooting at them at a pre-defined rate
    - If injured, the AI will run to find cover and heal up based on some pre-defined amount per-second
- Implemented spawning of AI in waves with the GameMode controlling it
- Implemented player respawning via the GameMode
- Implemented a custom Gameplay Ability System and refactored the game to use it for abilities such as player attacks
- Used Unreal's GameplayTags to implement
    - player buffs such as sprinting
    - enemy debuffs such as damage over time
    - setting a "flag" when obtaining a key item


Screenshots to follow soon.

<!-- 
Here are some screenshots:

<div id="kindCompanionCarousel" class="carousel slide" data-bs-theme="dark">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="4" aria-label="Slide 5"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="5" aria-label="Slide 6"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="6" aria-label="Slide 7"></button>
    <button type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide-to="7" aria-label="Slide 8"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/kindcompanion/kc-home-page.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-controlled-breathing.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-note-example.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-note-reminder.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-painting.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-settings-general.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-settings-reminder.png" class="d-block w-50" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/kindcompanion/kc-useful-knowledge.png" class="d-block w-50" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide="prev"  data-bs-theme="dark">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#kindCompanionCarousel" data-bs-slide="next"  data-bs-theme="dark">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="text-center">
    Kind Companion Screenshots
</div> -->

<br/>
<!-- 
*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).* -->

<!-- 
## Background

## App Design


## What did I learn?


## Final Thoughts
 -->

<p class="text-center">
{% include elements/ending-button.html link="/other-work" text="Back to Other Work" %}
</p>