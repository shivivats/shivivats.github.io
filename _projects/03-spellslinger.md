---
name: SpellSlinger
description: A 3D Augmented Reality mobile game where the player defends their house from enemies by activating different spells using physical cards.
image: /assets/images/games/spellslinger/spell-slinger-featured.png
tools: [ARCore, Unity, C#, 3D, Android]
---

# SpellSlinger

<i class="fab fa-github fa-1x"></i> [shivivats/SpellSlinger](https://github.com/shivivats/SpellSlinger)

SpellSlinger is a **3D Augmented Reality** mobile game where the player defends their house from enemies by activating different spells using physical cards. It was developed in 3 days for a course as part of my [Masters degree](https://www.aau.at/en/studien/master-game-studies-and-engineering/) in June 2019.

The game was built using the **Unity3D** engine and written in **C#**. I worked in a **team of four** on this, as a **programmer**. I was responsible for programming **everything related to AR** and the **core gameplay** of the game. The AR functionality was implemented using [Google ARCore for Unity](https://unity3d.com/partners/google/arcore).

The game can be found at [github.com/shivivats/SpellSlinger](https://github.com/shivivats/SpellSlinger), and here are some screenshots:

<div id="spellslingerCarousel" class="carousel slide" data-bs-theme="dark">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#spellslingerCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#spellslingerCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#spellslingerCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#spellslingerCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="/assets/images/games/spellslinger/spell-slinger-featured.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/spellslinger/ss-1.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/spellslinger/ss-2.png" class="d-block w-75" alt="...">
    </div>
    <div class="carousel-item">
      <img src="/assets/images/games/spellslinger/ss-3.png" class="d-block w-75" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#spellslingerCarousel" data-bs-slide="prev"  data-bs-theme="dark">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#spellslingerCarousel" data-bs-slide="next"  data-bs-theme="dark">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="text-center">
    <p>Spellslinger Screenshots</p>
</div>


<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*

## Background

As part of my Masters degree at my [University](https://www.aau.at/), I enrolled in a Augmented Reality course. It spanned four days, and after spending the first day and a half learning about the theory behind AR and some projects that used the technology, we were asked to form teams and spend the rest of the time making an AR project. I was part of a team of four, and with all of us being Game Studies and Engineering students, we decided to make an AR game. We used Unity3D with C# and the Google ARCore SDK to make AR work.

## Development Process

The idea of a “tower defence” game came to mind, and we decided on enemies and spell effects to ward them off as the base. The name of the game came from the fact that we wanted the player to be able to sling the spell cards and throw them in a direction. However, the ARCore SDK did not allow for that, so we skipped it and went for the player placing cards on the surface and spawning spells that way.

We had a dedicated project manager, and they made sure that the team was on the same page and regularly communicating with each other, which significantly improved our efficiency.

## Final Thoughts. What did I learn?

The development process was stressful for me as I tried to make some functionalities work, which ARCore did not allow traditionally. I ended up scrapping a lot of the design in favour of having a base that was easier to develop and expand on. Google ARCore was also only supported on a number of phones, which did not include my own. Thankfully, one of my teammates had a compatible phone. However, since I was the programmer for this project, testing changes was much more difficult when we weren't working at the same place.

Since this was my first time working with AR, I had no idea what to expect in terms of difficulty. I learned to RTFM before diving into development, as some functionalities I spent a while developing were already part of the SDK. I've wanted to work on another AR project since and plan to do that in the future, whether independently or as part of an organisation.


<p class="text-center">
{% include elements/button.html link="/projects" text="Back to Games" %}
</p>