---
layout: post
title:  "Deception Royale"
categories: [Game Jam Games, Team Projects]
tags: [2D, C#, Online Multiplayer, Unity]
image: assets/images/featured-images/deception-royale-featured.png
---

Deception Royale is a **2D top-down multiplayer battle royale** game, where each player tries to remain the last one standing. Up to 20 people can connect to a match and play against each other. The game was made as an entry to the [2nd AAU Winter Game Jam](https://itch.io/jam/2nd-winter-game-jam).
<!--more-->

The game was built using the **Unity3D** engine and written in **C#**. I worked in a **team of two** on this, as a **gameplay programme**r. A mini-map functionality was also added programmed by me. For the multiplayer, we used Unity’s **UNet API**.

Here’s a gameplay video with screen capture from two players:

<iframe width="560" height="315" src="https://www.youtube.com/embed/YGZs0rGlwcs" title="Deception Royale Gameplay Sample" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

It came with a booklet containing additional information about the game. It can be found on itch.io [here](https://shivivats.itch.io/deception-royale).

Following are some of my thoughts on the overall experience of developing this game. If you prefer to not read the rest of the post, you can go back to the blog home by clicking [here]({{ site.baseurl }}/index.html).

#### Background

My [university](https://www.aau.at/) was holding a [game jam](https://itch.io/jam/2nd-winter-game-jam) and me being part of the Game Studies and Engineering Masters program, had to participate in it. I decided to pair up with a friend of mine and as we wanted to expand towards new kinds of games, we knew before the jam started that we would either be making a 3D game or an online multiplayer game of sorts.

#### Design Choices

The jam had 3 themes: “90s”, “Fool”, “Manners”. These themes were hard to work with at first, but then they added the “diversifiers”, essentially features that we should try to implement in games to get extra points. My memory is fuzzy about it but I remember most of them, they were “battle royale”, “spontaneous combustion”, “all assets made for the game jam”, “a story with over 800 words”, “4 voiced characters”, “breaking the 4th wall”, “multiple art styles” and a “christmas theme”. Whew that was a lot. So we decided to make an online battle royale but considering neither of us had experience making 3D games at the time, we stuck with 2D.

We went with a Christmas theme, with presents and Christmas trees, with a way for players to implement bombs that were disguised as presents (to “fool” the other players and it wasn’t good “manners” to take a present then replace it with a bomb). All the assets were made by us during the jam and there was combustion but we were having trouble implementing the other diversifiers. So we came up with an idea to include a printed booklet with a story, which would satisfy the word requirement, would break the 4th wall and when read aloud would be voiced by 4 different people.

In the end it ended up being a game that was liked by people due to its multiplayer feature. People were having fun playing with their friends and we were glad that we were able to make a game that was enjoyable.

#### What I learnt

Online multiplayer was not as easy to implement as me and my teammate had thought in the beginning. The basics worked, but we had trouble customising and expanding on the base that we had implemented. It was a stressful time with only getting a few hours of sleep each night, and I’ve learnt to not underestimate multiplayer and to also not stress myself out to the point of me not wanting to work on the game and just giving up. I have avoided as stressful game jams since and have prioritised getting enough sleep and not feeling tired.