---
layout: post
title:  "SpellSlinger"
#author: Shivi
categories: [Team Projects, University Projects]
tags: [3D, Android, Augmented Reality, C#, Unity]
image: assets/images/featured-images/spell-slinger-featured.png
image_sliders:
  - slider_spellslinger
featured: true
#hidden: true
---

SpellSlinger is a **3D Augmented Reality** mobile game where the player defends their house from attacking enemies by activating different spells using their cards. It was developed for a course as part of my [Masters degree](https://www.aau.at/en/studien/master-game-studies-and-engineering/), in 3 days.
<!--more-->

The game was built using the **Unity3D** engine and written in **C#**. I worked in a **team of four** on this, as a **programmer**. I was responsible for programming **everything related to AR** and the **core gameplay** of the game. The AR functionality was implemented with the help of [Google ARCore for Unity](https://unity3d.com/partners/google/arcore).

Here are some screenshots:

{% include slider.html selector="slider_spellslinger" %}

The game can be found on itch.io [here](https://github.com/shivivats/SpellSlinger).

Following are some of my thoughts on the overall experience of developing this game. If you prefer to not read the rest of the post, you can go back to the blog home by clicking [here]({{ site.baseurl }}/index.html).

#### Background

As part of my Masters degree at my [University](https://www.aau.at/), I enrolled into a course regarding Augmented Reality. It spanned 4 days and after spending the first day and half learning about the theory behind AR and some projects that made use of the technology, we were asked to form teams and spend the rest of the time making an AR project. I was part of a team of four and, with all of us being Game Studies and Engineering students, we decided to make an AR game. We used Unity3D with C# for it, and the Google ARCore SDK to make AR work.

#### Design Choices

The idea of a “tower defence” game came to mind, and we decided to have enemies and spell effects to ward them off. The name of the game came from the fact that we wanted the player to be able to sling the spell cards and throw them in a direction, however the ARCore SDK did not allow for that, so we skipped it and went for the player placing cards on the surface and spawning spells that way.

We had a dedicated project manager and they made sure that the team was on the same page and regularly communicating with each other, which greatly improved our efficiency.

The development process was stressful for me as I tried to make some functionalities work, which ARCore did not allow traditionally. I ended up scrapping a lot of the design in favour of having a base that was easier to develop and expand on. Google ARCore was also only supported on a number of phones, which did not include my own. Since I was the programmer for this project, it made testing changes much more difficult when we werent working at the same place.

#### What I learnt

Since this was my first time working with AR, I had no idea what to expect in terms of difficulty. I learnt to RTFM before diving into development, as some functionalities I spent a while developing, were already part of the SDK. I’ve wanted to work on another AR project since and plan to do that in the future, whether independently or as part of an organisation.