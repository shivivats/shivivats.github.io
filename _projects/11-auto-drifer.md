---
name: Auto Drifter
tools: [C#, Unity, 2D]
image: /assets/images/games/autodrifter/autodrifter-featured.png
description: A top-down 2D racing game where the player competes against the AI in a race, drifting around corners while the car automatically accelerates.
---

# Auto Drifter

<i class="fab fa-github fa-1x"></i> [shivivats/AutoDrifter](https://github.com/shivivats/AutoDrifter)

Auto Drifter is a **top-down 2D racing** game in which the player competes against the AI in a race, drifting around corners while the car automatically accelerates. The game was made in July 2019 for a course as part of my [Masters degree](https://www.aau.at/en/studien/master-game-studies-and-engineering/), with the condition that the game had to only be played with one button.

I made two versions of the game- one played with one button where the player can only turn counter-clockwise, and another where the player can turn either direction using two buttons. The game was built using the **Unity3D** engine and written in **C#**. I worked alone on this, hence I programmed the **gameplay** and **created the art**. The game does not have any audio.

I'd like to highlight how I designed the AI. I figured out the "optimal racing line" and then calculated the turning points along that line. I then made an array of these points and had the AI go through the array in sequential order. This made the AI quite challenging to beat, but still simple in implementation. With my knowledge now, I'd try to implement a simple neural network agent which could be applied to any track in the game. The agent could also be trained for multiple difficulty levels, which would add more depth to the gameplay.

The one-button and two-button versions of the game can be found at [zarroc.itch.io/auto-drifter-two-button-version](https://zarroc.itch.io/auto-drifter-two-button-version) and [zarroc.itch.io/auto-drifter](https://zarroc.itch.io/auto-drifter), respectively. Here’s a gameplay sample of the two-button version:

<div class="row">
    <div class="col-sm mt-3 ratio ratio-16x9 center-block">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/5ajv9FNBEp8" allowfullscreen class="w-80 p-3"></iframe>
    </div>
</div>
<div class="text-center">
    Auto Drifter Gameplay Sample
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*

## Background

This is another project I made as part of my [Masters degree](https://www.aau.at/en/studien/master-game-studies-and-engineering/) at my [University](https://www.aau.at/en/). This course focused on game design, and we were tasked to make a game playable using only a single button as a final project. Since I love cars and wanted to make a game focusing on cars for a while, I went with a drifting/racing theme.

## Development Process

The game revolved around the player’s car automatically accelerating and the player using just one key to rotate the vehicle in a direction to manoeuvre around the circuit. I modelled the track by taking inspiration from various Formula 1 circuits from across the globe. I initially had planned to add a car customiser to the game, but I decided to skip it since controlling it with just one button would have been troublesome for the player.

The decision to add an AI was made to give the player a sense of competition and show them a bit of the “driving line” in case they were confused.

## Final Thoughts. What did I learn?

I had a lot of fun designing and developing this game, as I am passionate about cars. I am happy with how the game turned out. I even made a two-button version to give the player more control over their car.

I learnt that games do not need to be complicated to be fun. They can be as simple as a racing/drifting game using only one button!

<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>