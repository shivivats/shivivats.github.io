---
name: Deception Royale
tools: [C#, Unity, 2D, Online Multiplayer]
description: a 2D top-down multiplayer battle royale game, where each player tries to remain the last one standing by planting hidden bombs to take out others.
image: /assets/images/games/deceptionroyale/deception-royale-featured.png
---

# Deception Royale

Deception Royale is a **2D top-down multiplayer battle royale** game, where each player tries to remain the last one standing. Up to 20 people can connect to a match and play against each other. The game was made as an entry to the [2nd AAU Winter Game Jam](https://itch.io/jam/2nd-winter-game-jam), held in December 2018.
s
The game was built using the **Unity3D** engine and written in **C#**. I worked in a **team of two** on this, as a **gameplay programme**r. A mini-map functionality was also added programmed by me. For the multiplayer, we used Unity’s **UNet API**.

The game came with a booklet containing additional information about the game, mostly  to satisfy the 800 word challenge of the game jam (the organisers let it slide). The game can be found at [zarroc.itch.io/deception-royale](https://zarroc.itch.io/deception-royale), and here’s a gameplay video with screen capture from two players:

<div class="row">
    <div class="col-sm mt-3 ratio ratio-16x9 center-block">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/YGZs0rGlwcs" title="Deception Royale Gameplay Sample" allowfullscreen class="w-80 p-3"></iframe>
    </div>
</div>
<div class="text-center">
    Deception Royale Gameplay Sample
</div>

<br/>

*Following are some of my thoughts on the overall experience of developing the app. If you prefer to not read the rest of the post, you can go back to the portfolio home by clicking [here](/projects).*


## Background

My university was holding a game jam, and I, being part of the Game Studies and Engineering Masters program, had to participate in it. Well, I would've participated anyway. I decided to pair up with a friend of mine, and as we wanted to expand towards new kinds of games, we knew before the jam started that we would either be making a 3D game or an online multiplayer game of sorts.

## Development Process

The jam had three themes: “90s”, “Fool”, and “Manners”. These themes were initially complex to work with, but then organisers added the “diversifiers”- essentially features that we should try to implement in games to get extra points. My memory is fuzzy about it, but I remember most of them. They were “battle royale”, “spontaneous combustion”, “all assets made for the game jam”, “a story with over 800 words”, “4 voiced characters”, “breaking the 4th wall”, “multiple art styles”, and a “christmas theme”. Whew, that was a lot. After some deliberation, my team decided to make an online battle royale. But considering neither of us had experience making 3D games, we stuck with 2D.

We went with a Christmas theme, with presents and Christmas trees dotting the map. The players could implement bombs that were disguised as presents (to “fool” the other players, plus it wasn’t good “manners” to take a gift and then replace it with a bomb). We made all the assets during the jam and even added combustion, but we had trouble implementing the other diversifiers. So we came up with an idea to include a printed booklet with a story, which would satisfy the word requirement, would break the 4th wall, and, when read aloud, would be voiced by four people.

Ultimately, it ended up being a game that people liked due to its multiplayer feature. People were having fun playing with their friends, and we were glad that we were able to make an enjoyable game.

## Final Thoughts. What did I learn?

Online multiplayer was more challenging to implement than my teammate, and I had thought initially. The basics worked, but we spent a lot of time customising and expanding the base we had implemented. It was a stressful time with only a few hours of sleep each night, and I’ve since learned not to underestimate multiplayer and, more importantly, to not stress myself out to the point of not wanting to work on the game and just giving up. I have avoided stressful game jams since and have prioritised getting enough sleep and not crunching so much.


<p class="text-center">
{% include elements/ending-button.html link="/projects" text="Back to Games" %}
</p>