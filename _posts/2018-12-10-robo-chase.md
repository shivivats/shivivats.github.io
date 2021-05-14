---
layout: post
title:  "Robo Chase"
categories: [Game Jam Games, Team Projects]
tags: [2D, C#, Local Multiplayer, Unity]
image: assets/images/featured-images/robo-chase-featured.png
image_sliders:
  - slider_robochase
---

Robo Chase is a **local two-player retro platformer**, with one player playing as a cop chasing to catch the other player playing as a robot, while avoiding a wall of laser coming at them, among other obstacles and traps. It’s played on a split screen and the game ends when either player dies, the cop catches the robot or the robot makes it to the end of the level. The game was made as an entry to the [Retro Platformer Jam](https://itch.io/jam/retro-platformer-jam), and we ended up getting 1st place in the “Technical” category.

The game was built using the **Unity3D** engine and written in **C#**. I worked with a friend on it and while he took up the role of artist and programmer, I **mainly programmed**. We implemented **two levels** (an easy and a difficult one), chosen at random for the players. The game can also be played in single-player mode with the players as the cop trying to catch the robot.

Some screenshots of the game are shown below.

{% include slider.html selector="slider_robochase" %}

The game can be found on itch.io [here](https://shivivats.itch.io/robo-chase).

Following are some of my thoughts on the overall experience of developing this game. If you prefer to not read the rest of the post, you can go back to the blog home by clicking [here]({{ site.baseurl }}/index.html).

#### Background

I had just moved to Austria a few weeks ago, I knew no one and barely spoke the language. However I made a friend quite early on and we decided that what better way to get to know each other than to work on a game together! We picked that [game jam](https://itch.io/jam/retro-platformer-jam) in particular as it fell on the only free weekend we had before the game jam held at our university. We were already planning to participate in the [university’s game jam](https://itch.io/jam/2nd-winter-game-jam) as a team so we wanted to get some experience working together beforehand.

#### Design Choices

We both had prior programming experience, and also experience with Unity so we decided to make things a bit harder for ourselves by trying to program a two-player game as neither of us had done that before. We were also excited that the jam dictated the game should be played with a controller since, at the time, we didn’t know how to configure Unity to use a controller and we wanted to learn.

The jam’s theme was Cyberpunk. So we decided to go with the classic “robot gone rogue” setting, with a cop trying to catch it. The game was a lot of firsts for us, and we scrapped quite a few features that we had planned, simply because we didn’t estimate how long it would take for certain core features to be implemented. We also intended for the game to be two-player only but we soon realised that the person rating the game would be playing alone so we implemented a single-player mode, which wasn’t part of our initial plan.

The game ended up being somewhat rushed, but we implemented the core features and the final game had the essence that we wanted to go for.

#### What I learnt

As with most projects I make, I challenge myself to try something I haven’t tried before. For this, it was multiplayer, audio controller and working in a team. I experienced what it was like having to match another person’s pace and to meet their expectations. I’ve definitely learnt from it and applied it to other projects. It was also one of my first times working with Unity3D and C#, and since then I’ve grown much more confident at using those tools.

In the end, the game holds a special place in my heart as I believe sitting together and gaming with your friends is one of the best experiences in life and I was glad that we could make a game that somewhat fit the dying couch multiplayer genre. Because, even though it was an unfinished product, it was still fun to play with a friend!