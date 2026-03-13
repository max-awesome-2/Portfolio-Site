---
layout: page
title: Hamster Shotgun Death Tower (2025)
description: The title is self explanatory.
img: assets/hsdt/img/hsdt.png
importance: 1
category: WIP
related_publications: false
---

<h2>Summary</h2>
<p><b>Hamster Shotgun Death Tower</b> is a small project I'm working on. It started out as an experiment - I thought of the idea of a movement system where the character bounces around the screen from the recoil of a shotgun blast, and decided to try implementing it in a very small demo, focusing on the juiciness and feel of the action.

## Chaotic Rotation
The first iteration of the game had the player controlling the character's movement with only one button. The hamster would constantly  be rotating, and the player could hit the spacebar to shoot in the direction the hamster was currently facing. After every shot, the rotation direction and speed of the hamster would be set randomly.

Needless to say, this ended up being ridiculously hard to control. I had intended it to be finicky in a chaotic way, but it just didn't feel good at all, so I decided to try changing it so that the player could aim the hamster's rotation with the mouse. Although it took a bit of the concept's unique identity away, it felt much better to control, so I stuck with it.

## Adding Nuance
I initially imagined that the game would have hazards such as enemies or terrain hazards that the player would have to dodge - this would test their mastery with the unusual movement system. But I also figured that having the shotgun blast as the player's only method of movement might be overly limiting. Say, for example, the player wants to quickly shoot a target in front of them, but there's a hazard directly in the opposite direction. Shooting the target would launch them backwards into the hazard, so ideally they would reposition by shooting once and launching themselves off to the side, so they could shoot the target without being pushed back into the hazard. Unfortunately, the velocity at which the player was launched back by the shotgun blast was so fast that it was incredibly difficult to 'reposition' like that. I didn't want to lower the blast velocity (it felt pretty perfect), so I started thinking of other ways I might be able to let the player perform more intricate movements.

## The Wall
My first idea was to have some sort of a wall that the player could move with the mouse. That way, the player could put this wall between the hamster and the hazard, and it could bounce safely off. So as not to balance the power of this floating wall, I could change the speed at which the wall followed the mouse. I also had it always rotate to face the player, so that the largest surface area of the wall was facing the player at all times.

I tested this idea and it didn't feel so good. I hadn't taken into account the fact that making the wall 'always the face the player' meant that the closer the player got to the wall, the more drastically it would rotate. This made it look really unstable. I tried making the rotation lerp towards the target direction (rather than settings it instantly) and that looked better, but felt worse. It also just didn't really feel good to use the wall at. (This was also before I changed the movement so that the mouse controlled the rotation). So, I scrapped the wall and started thinking of other options.

## Slow-Mo Meter
I was struck with the idea of a 'slo-mo-meter'. At first it seemed like a bit of a cop-out - sort of uncreative solution to a problem that could definitely be solved in a lot of different ways. However, the more I thought about it, the more it seemed like a great idea. It allows the player to aim precisely, reposition in tight situations, or just take a breather, and having it tied to a resource bar makes room for skill expression - players are encouraged to use the absolute minimal amount of slo-mo, and players who have the reaction time to avoid using it at all can stockpile it for when they really need it. Sure enough, when I tried it out, it felt like the perfect complement to the main shooting mechanic. What I think is best about it is that rather than taking emphasis away from the main action of the game (like the floating wall does), it *adds* emphasis - it feels a lot more purposeful than something like a big floating wall, which sort of seems like a mechanic from an entirely different game frankensteined into this one.

## Zombies
To give the player an objective, I also added a health bar and zombies that the player can shoot. Running into the zombies takes a chunk out of the player's health bar, but if the player goes a few seconds without taking damage, their health starts regenerating. I also made it so killing zombies returns a small amount of the slo-mo meter (which also regenerates over time). The rate at which zombies spawn gradually increases over time, so the demo is a see-how-long-you-can-last type game.

## Juice
For a while, I focused on adding as much juice to the action as possible.

I added:
1. A screen shake effect whenever you shoot (naturally - a simple step, but it added a lot)
2. A muzzle flash animation I made in photoshop - after some tuning, I got something that I think looks super smooth in both regular speed and slo-mo.
3. A movement trail (using a LineRenderer) that <b>changes in slo-mo</b> into a trail of afterimages. This one was a bit tougher to implement, but the final product turned out just gorgeous and I'm very proud of it. 

I added a blast of blood particles when a zombie gets killed, plus a blood stain that gets projected onto the wall.

## Neausea Inducer
At this point, I had the main mechanic feeling very good, and I wanted to take the game further. Unfortunately, I found myself completely stumped as to what direction I wanted to take the game in. I didn't want to go the route of a simple

<h2>Notable Features</h2>

<h2>Lessons</h2>


