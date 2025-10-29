---
title: "Paradox Clue"
draft: false
comments: false
socialShare: true
toc: false
cover:
  src: "cover.png"
  caption: "Detective Jackal's office."
date: "2024-11-05"
tagline: "Whodunit? Nah, howdunit."
---

[_Paradox Clue_](https://edneedsbread.itch.io/paradox-clue) is a game developed
for the 2024
[Game Development Project course at University of Gothemburg](https://www.gu.se/en/study-gothenburg/game-design-technology-masters-programme-n2gdt).
The theme for this project was Public Domain, and for such, we had to choose a
piece of publicly owned media to make a game out of. We chose two: _The Starry
Night_, by Vincent Van Gogh, and _Strange Case of Dr Jekyll and Mr Hyde_ by
Robert Louis Stevenson.

Developed with **Godot** version 4.3.

<!--more-->

The game consists of two levels that are meant to play a back-and-forth of
creating a hypothesis, and acting out how a scenario might have happened. This
constantly cause paradoxes to occur where you might have reached a place before
you even opened the door to that location, which was part of the almost
deliriant spirit that we strived to achieve.

{{< itch 3056327 >}}

## Contributions

### Swapping and Transitions

A lot of the game depended on being able to toggle on and off between modes by
selecting the correct things to swap between in each mode, and seamlessly
trigger a transition between the two. I worked on swapping components to make
the transition between modes possible, and also gave them good looking
transitions for when specific things happen.

{{< video src="captures/swap.mp4" autoplay="false" controls="true" loop="false" >}}

### Graphics

One of the things we settled on from the very start was that while it is true
that you play two characters, each character sees people in a different way.

Detective Jackal sees people as two-dimensional. Flat personalities, but,
nevertheless, people. So I made sure to try to express said frame of mind via a
set of two billboards, one locked to the Y axis, and one always facing the
player. That way, while these characters were motionless, they still felt like
they had some manner of life to them, with eyes that followed you around in the
scene.

{{< video src="captures/billboard.mp4" autoplay="false" controls="true" loop="true" >}}

The Hound, however, sees people as nothing more than obstacles. They're danger
where they stand, and must be avoided at all costs. I worked on a shader that
would help express this frame of mind. While characters remain static, their
outlines are uneasy and erratic. They spell out caution visually, forces to be
reckoned, and avoided. While humans do catch you red-handed, animals don't care
for the Hound's presence, and remain unbothered. So while they share the same
shader properties, its a much calmer view for them.

{{< video src="captures/point.mp4" autoplay="false" controls="true" loop="true" >}}

{{< video src="captures/cat.mp4" autoplay="false" controls="true" loop="true" >}}

### Narrative

I did a good deal of dialogue for this game. I wanted to retain the themes
reminiscent of film noir, while introducing our bizzarre and at times absurdist
commentary sprinkled throughout conversations and introspections.

Dialogue was sprinkled throughout the game, across NPC conversations and flavor
text through intractable objects in the scene. Here's a snippet that I liked
about detective Jackal pulling a random book from a bookshelf.

```txt {class="codeblock_limit"}
Gymnasium Romantics - Love Finds its Whey
Youkai and Other Oriental Spirits
IBM 370-165 - The Million Byte Computer
Unabridged Collection of Poems by J. J. Jeorjes
Weekend's Summer - The Winter of the Working Week
Coffee, and How to Brew It
How to be Funny, by P. Gliacci
Extraterrestrials - I've Met Them; Read All About It
1948
This Book Will be Very Sad if You Don't Read It
Patterns, Sequences, and Chains - How Things Be and Do
Spirituality for the Non-Believer
God-fearing for the God-loving
Comic Strips From a Future Era
Politics Reloaded
Anthropology of the Inanimate
Water - A Ruse?
They Wouldn't Let Me Sell This Book in Hardcover - A Chronicle of Woe
Otters and Their Schemes
The Alexandria of Libraries
Mechanical Physics In Four-Dimensional Hyperspaces
Yawns, and How to Spread Them
My First Book of Statistics - Bedtime Stories and Poems
Metallurgy - A Three Act Play
The Melancholy of Sad Songs
The Sundering of Vitalicio
Tale of Two Dogs - The Grand Chase
Diccionario Español a Ingles
Headaches, And How to Cause Them
Lions of Passion; Wolves of Resolve
```

## Conference

The game had a live demo at the **Intro to Games Research & Game Development
Project Conference 2024**.

![Conference](conference.jpg)
