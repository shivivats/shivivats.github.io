---
layout: page
title: Robo Chase
description: local two-player retro platformer
img: /assets/img/games/robochase/robo-chase-featured.png
importance: 1
category: work
related_publications: true
---


Robo Chase is a **local two-player retro platformer**, with one player playing as a cop chasing to catch the other player playing as a robot. Both players have to avoid a wall of laser coming at them, among other obstacles and traps. It’s played on a split screen and the game ends when either player dies, the cop catches the robot, or the robot makes it to the end of the level.

The game was made as an entry to the [Retro Platformer Jam](https://itch.io/jam/retro-platformer-jam), and we ended up getting 1st place in the “Technical” category. It was built using the **Unity3D** engine and written in **C#**. I worked with a friend on it and while he took up the role of artist and programmer, I **mainly programmed**. We implemented **two levels** (an easy and a difficult one), chosen at random for the players. The game can also be played in single-player mode with the players as the cop trying to catch the robot.

The game can be found at [zarroc.itch.io/robo-chase](https://zarroc.itch.io/robo-chase). Here are some screenshots and a gameplay sample:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/games/robochase/robo-chase-featured.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/games/robochase/robochase-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
<div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/games/robochase/robochase-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/games/robochase/robochase-3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some caption here.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0 embed-responsive embed-responsive-16by9 center-block">
        <iframe class="embed-responsive-item" width="640" height="360" src="https://www.youtube.com/embed/pC7kbHzRbIA?si=E2w1VmgWXESnpd6s" allowfullscreen></iframe>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

<div class="modal in" id="viewImg" tabindex="-1" role="dialog">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
      </div>
      <div class="modal-body">
        <div id="imgViewer" style="overflow-x: scroll;">
        </div>
      </div>
    </div>
  </div>
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

