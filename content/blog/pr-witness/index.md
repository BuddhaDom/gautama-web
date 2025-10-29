---
title: "pr//WITNESS"
draft: false
comments: false
socialShare: true
toc: false
cover:
  src: "cover.png"
  caption: "Dr. Armaan in his appointment with the protagonist, Dwade Romer."
date: "2025-01-21"
tagline: "Please. Take these pills."
---

[pr//WITNESS](https://marwo.itch.io/prwitness) is a game developed for the 2024
[Interactive and Linear Storytelling with digital media course at the University of Gothenburg](https://www.gu.se/studera/hitta-utbildning/interaktivt-och-linjart-berattande-med-digital-media-dit998).
It is a 10-15 minute linear story game in which you play the role of Dwade
Romer, who is experiencing odd feelings after having taken an experimental
medication.

Made with **Unreal Engine 5**.

<!--more-->

{{< itch 3249252 >}}

## The Setting

Dwade Romer struggles with a light case of schizophreniform disorder. Gets by
with the medicine he's been prescribed, but struggles with its side effects:
dizziness and numbness.

A new study at _Elwood and Co._, the company where his fiancée, Lucia Duarte,
works as a biochemist. Upon arriving to the _Elwood and Co._ pharmaceutical
branch, he is met with Dr. Wilmer Armaan.

Dwade is given the experimental pills by Dr. Armaan. This is where things start
taking an odd turn.

## Motion Capture

{{< video src="captures/mocap_development.mp4" autoplay="false" controls="true" loop="true" >}}

{{< video src="captures/mocap_result.mp4" autoplay="false" controls="true" loop="true" >}}

We believe this story required more realistic looking visuals than we usually
use within our projects. It had to be more cinematic. This is why we decided to
use Unreal Engine, as it has the Metahuman system.

Since we wanted the game to have very distinct scenes, we needed motion capture
to really capture the events that transpire in the game.

This proved to be doable, albeit challenging. We didn't have access to
conventional motion capture equipment, but we used a combination of video-based
motion capture tools. Namely,
[Rokoko Vision](https://www.rokoko.com/products/vision) for body motion capture,
and [Live Link Face](https://apps.apple.com/us/app/live-link-face/id1495370836)
for facial.

Since facial and body motion capture had to be done separately, we opted to
record audio with facial motion capture recording, and then the scene would be
performed for the purposes of body motion capture.

I was the body actor for all characters, and voice for Dr. Armaan.

## Datamoshing

{{< video src="captures/datamosh_many.mp4" autoplay="false" controls="true" loop="true" >}}

{{< video src="captures/datamosh_single.mp4" autoplay="false" controls="true" loop="true" >}}

The whole story is centered around the
[datamoshing artifacting](https://www.youtube.com/shorts/f4PFNsDQNkM) effect. We
used this effect to show moments in which Dwade can't trust his own vision.

To implement it, we
[acquired an asset](https://www.fab.com/listings/f54fa19f-b19a-4330-88a6-a467f6a00bca)
that supported building datamoshing effects, and liberally created interesting
transitions, relocating the player into different rooms, toying with their
perception.

In the game, the cause of this effect is a drug developed in secret by _Elwood
and Co._: **Ophtalmolysis**. Breakdown of the eyes.

The implementation was largely done by one of our team members, and I built the
sequences in which the effect triggers.

## Storytelling

We wanted to make a story that was fiction-first. We chose a gimmick to center
our story around, which was the use of datamoshing artifacting, and built the
story around how it could present itself to the player, and more importantly, to
the character experiencing it.

With this, we decided to create a story about medical malpractice. Dr. Armaan
has inserted himself into this position in order to personally attack Dwade.

To tell this story, we decided to go with a linear approach, with constant
flashbacks to give more context about the events unfolding in front of the
player. Since we had the datamoshing artifacting gimmick as our core, we used it
ton diegetically trigger these flashback cutscenes, and slowly reveal to the
player the true nature of their situation.

I took part in the creation of the story, writing of the characters, and their
dialogues.

![Planning whiteboard](whiteboard.png)
